pipeline {
    agent none
    stages {
        stage('MDC operator tests') { steps { echo 'Hello world!' } }
        stage('Services tests') {
            parallel {
                stage('MDC') {
                    stages {
                        stage('API tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('UI tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('UPS') {
                    stages {
                        stage('Operator tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Karma tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('SSO') {
                    stages {
                        stage('Operator tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Appium tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Metrics') {
                    stages {
                        stage('Operator tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Karma tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Sync') {
                    stages {
                        stage('Operator tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                        stage('Karma tests') {
                            steps {
                                echo 'Hello world!' 
                            }
                        }
                    }
                }
                stage('Security') {
                    stages {
                        stage('Karma tests') {
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
                stage('SSO tests') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Security tests') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Sync tests') {
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
