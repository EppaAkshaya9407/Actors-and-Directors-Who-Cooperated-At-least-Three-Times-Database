# Actors-and-Directors-Who-Cooperated-At-least-Three-Times-Database
select actor_id,director_id from ActorDirector group by actor_id,director_id having count(*)>=3;
