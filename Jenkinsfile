pipeline {
    agent none
    stages {
        stage('MDC operator test') { steps { echo 'Hello world!' } }
        stage('Services tests') {
            parallel {
                stage('MDC') {
                    stages {
                        stage('API test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('UI test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('UPS') {
                    stages {
                        stage('Operator test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Karma test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('SSO') {
                    stages {
                        stage('Operator test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Appium test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Metrics') {
                    stages {
                        stage('Operator test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Karma test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Sync') {
                    stages {
                        stage('Operator test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Karma test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Security') {
                    stages {
                        stage('Karma test') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
            }
        }
        stage('Services + Metrics tests') {
            parallel {
                stage('SSO test') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Security test') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Sync test') {
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
