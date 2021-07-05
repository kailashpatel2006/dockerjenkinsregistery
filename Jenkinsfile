node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'kailashpatel') {

        def customImage = docker.build("kailashpatel/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
