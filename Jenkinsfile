node ('os-patch'){
    // Mark the code checkout 'stage'....
    stage 'Checkout'

    // Checkout code from repository
    checkout scm

    // Mark the code build 'stage'....
    stage 'Build'
    // Run the maven build
    sh "gradle -PupdatePackageList=screen createPackageWithUpdates"
}