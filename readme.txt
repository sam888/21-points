
 This is an exercise of refactoring the JHipster app 21-points (checked out from https://github.com/mraible/21-points)
 from a single gradle project into multi-gradle projects.
 
 The check-in history of refactoring process should serve as a good example of how to do the same thing to an existing
 JHipster project using Gradle.
 
 The refactored 21-points project is fully functional as before and has structure 
 
     Root project '21-points'
        +--- Project ':21-points_dao' - 21-points_dao
        +--- Project ':21-points_dto' - 21-points_dto
        +--- Project ':21-points_model' - 21-points_model
        +--- Project ':21-points_service' - 21-points_service
        +--- Project ':21-points_util' - 21-points_util
        \--- Project ':21-points_web'

 To run, simply type 'gradlew bootRun' in command line at root project directory.
 
 
 5-Jan-2017
 Samuel Huang
 