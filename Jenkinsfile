          pipeline {
			agent any 
			stages {
				stage('BUILD') {
					steps {
						sh '''
							#!/bin/bash 
							echo "Build stage in Jenkinsfile"
							sleep 5
						'''
					}
				}
				stage('TEST1') {
					steps {
						sh 'echo "Test1 stage in Jenkinsfile";sleep 5'
					}	
				}
				stage('TEST2') {
					steps {
						sh 'echo "Test2 stage in Jenkinsfile";sleep 5'
					}	
				}
				stage('DEPLOY') {
					steps {
						sh 'echo "Final DEPLOY stage in Jenkinsfile";sleep 5'
					}
				}	
				stage('STATUS') {
					steps {
						sh 'echo "pipeline job is completed";sleep 5'		
					}
				}
			}
		}
