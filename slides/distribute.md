##  Present & Distribute

> Oh no... My computer crashed...

or

> Can you sent me the slides?

- `grunt deploy`
```coffee
    grunt.registerTask 'deploy',
        'Deploy to Github Pages', [
            'dist'
            'buildcontrol'
        ]
```

→ it's already in the "cloud" 
