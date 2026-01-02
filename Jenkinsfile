pipeline{
    agent {
        node{
        label "maven"
    }
    }
    stages ("code checkout")
    {
        steps {
            git branch : 'main', url : 'https://github.com/ThanushKumarV/tweet-trend-new.git'
        }
    }
}