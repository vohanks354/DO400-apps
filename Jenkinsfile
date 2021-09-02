node{
    stage ('Install Dependencies') {
        dir ('exchange-cli') {
            sh "npm install"
        }
    }

    stage ('Unit Test') {
        dir ('exchange-cli') {
            sh "npm run test:unit"
        }
    }
}