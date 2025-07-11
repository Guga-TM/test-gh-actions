pipeline {
    agent {
       label "master-agent"
    }
    stages {
      stage('cat file') {
        steps {
          sh '''#!/bin/bash
cat 1.txt
'''
        }
      }
    }
}
