pipeline {
    agent none
    stages {
        stage('MDC operator') { steps { echo 'Hello world!' } }
        stage('Services operators') {
            parallel {
                stage('UPS') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('App RH SSO') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Metrics') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Data Sync') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
            }
        }
        stage('Services') {
            parallel {
                stage('UPS') {
                    parallel {
                        stage('Android') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('iOS') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('App RH SSO') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Metrics') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Data Sync') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
            }
        }
    }
}
