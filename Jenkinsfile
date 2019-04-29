pipeline {
    agent none
    stages {
        stage('MDC operator') { steps { echo 'Hello world!' } }
        stage('Services') {
            parallel {
                stage('MDC') {
                    stages {
                        stage('API') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('UI') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('UPS') {
                    stages {
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('SSO') {
                    stages {
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Metrics') {
                    stages {
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Sync') {
                    stages {
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Security') {
                    stages {
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
            }
        }
        stage('Services + Metrics') {
            parallel {
                stage('SSO') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Security') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Sync') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
            }
        }
        stage('Showcase') {
            steps {
                echo 'Hello world!' 
            }
        }
    }
}
