properties([parameters([string(defaultValue: 'Hello', description: 'How should I greet the world?', name: 'Greeting')])])

node {
    echo "${params.Greeting} World!"
    echo ${env.BRANCH_NAME}
    echo ${env.CHANGE_ID}
}