podTemplate(label: label, containers: [
  containerTemplate(name: 'carbon-jessie', image: 'node:carbon-jessie', command: 'npm install', ttyEnabled: true)
]),
node() {
    echo "Your Pipeline works!"
    sh('ls -la')
    sh('echo hello')
    sh('npm install')
    sh('npm test')
}