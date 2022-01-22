pipeline {

	agent any

	parameters {
		choice(name: 'buildTool', choices: ['gradle', 'maven'], description: 'Indicar herramienta de construcción')
	}

	stages{
		stage('Pipeline'){
			steps{
				script{
					
					println 'Pipeline'
					
                    if (params.buildTool == "gradle") {
                        println 'Ejecutar gradle'
                    } else {
                        println 'Ejecutar maven'
                    }
                    
				}
			}
		}
	}
}
