
node{

    agent {

        label 'sample_1'

    }

    stage('Checkout'){

        echo "checkedout"
    }

    stage('compile-package'){

        echo "package completed"
    }

    stage(' Maven Test') {
            echo "test completed"
        }
    stage('Push Image') {
         echo "wait for push"
    }
}
