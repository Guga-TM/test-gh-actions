pipeline {
    agent {
       label "master-agent"
    }
    stages {
      stage {
        steps {
          sh '''#!/bin/bash
cat 1.txt
'''
        }
      }
    }
}
