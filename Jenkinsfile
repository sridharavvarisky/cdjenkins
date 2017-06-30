pipeline {
    agent any
    stage("build"){
        steps {
            echo "Building"
            echo "Run unit tests"
            echo "Run integration tests"
            echo "Build success"
        }
    }

    stage("acceptance") {
        steps {
            echo "Run acceptance tests"
            echo "Success"
        }
    }

    stage("performance") {
        steps {
            echo "Run performance tests"
            echo "Success"
        }
    }

    stage("end-to-end") {
        steps {
            echo "Run end to end tests"
            echo "Success"
        }
    }

    stage("create-and-push-docker-image") {
        steps {
            echo "Run end to end tests"
            echo "Success"
        }
    }

    stage("integration") {
        steps {
            echo "Run integration tests"
            echo "Success"
        }
    }

    stage("deploy") {
        steps {
            echo "Deploy in all non prod environments"
            echo "Success"
        }
    }

    stage("release") {
        steps {
            echo "Deploy to production"
            echo "Success"
        }
    }
}