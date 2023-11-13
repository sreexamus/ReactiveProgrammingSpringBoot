# ReactiveProgrammingSpringBoot
Write Reactive Programs on Spring boot using spring webflux.


All Takeaways:-

1. Taditional REST API:-
          a. Imperative Coding design(Top to Down coding apporach)
          b. its synchronous call.
          c. they are blocking apis.
          d. No Back Pressure Support
          e. Limit on number of concurrent users. As it has Thread per request model where thread is created for each request. If the
             thread pool has n objects then only n requests can be handled at a time.
