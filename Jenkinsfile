node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub_praveen') {

        def customImage = docker.build("praveenshell123/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}