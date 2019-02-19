#!/bin/groovy
pipeline{
agent any
    stages{
        stage ('Job URL'){
            steps{
                sh "echo ${JOB_URL}"
            }
        }
        stage ('Get Branch'){
            steps{
                sh "echo $BRANCH_NAME"
            }
        }
    }
}