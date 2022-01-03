          pipeline {
			agent any 
			stages {
				stage('BUILD') {
					steps {
						sh '''
							#!/bin/bash 
							echo "Build stage in Jenkinsfile"
						'''
					}
				}
				stage('TEST1') {
					steps {
						sh 'echo "Test1 stage in Jenkinsfile"'
					}	
				}
				stage('TEST2') {
					steps {
						sh 'echo "Test2 stage in Jenkinsfile"'
					}	
				}
				stage('DEPLOY') {
					steps {
						sh 'echo "Final DEPLOY stage in Jenkinsfile"'
					}
				}	
				stage('STATUS') {
					steps {
						sh 'echo "pipeline job is completed"'		
					}
				}
			}
		}
