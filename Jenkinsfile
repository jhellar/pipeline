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
                        stage('Operator') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('SSO') {
                    stages {
                        stage('Operator') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Metrics') {
                    stages {
                        stage('Operator') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Sync') {
                    stages {
                        stage('Operator') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Integration') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Security') {
                    steps {
                        echo 'Hello world!' 
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
