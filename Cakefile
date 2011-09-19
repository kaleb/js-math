{exec, spawn} = require 'child_process'
path = require 'path'
file = 'math'
task 'build', 'Build the coffee', (options) ->
    exec "coffee --compile #{file}.coffee", (error, stdout, stderr) ->
        if error
            console.log "JS build failed."
        else
            console.log "JS build succeded."
            exec "dox --title #{file} #{file}.js > index.html", (error, stdout, stderr) ->
                if error
                    console.log "Doc gen failed."
                else
                    console.log "Doc gen succeded."
