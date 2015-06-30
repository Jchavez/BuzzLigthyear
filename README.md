# Install prerequisites
* Git
  - `git --version` - v1.9.5
* Python 
  - `python --version` - v2.7.10

* Install Node.js
  - `node --version` - v0.12.4
  - `npm --version` - v2.10.1

* Install StrongLoop
  - `npm install -g strongloop`

# Create APP
* `slc loopback`

# Create Data Source
* `slc loopback:datasource`
* Install the corresponding connector
    -`npm install --save loopback-connector-mysql`
* Add Properties 
    -`"host":"localhost","database":"buzz_ligthyear","username":"root","password":"123456","port":"3306"`

# Create Model
* `slc loopback:model`

# Run the application
* `node .`
