[mongo-sync](https://github.com/sheharyarn/mongo-sync)
======================================================

> _Sync Remote and Local MongoDB Databases in Bash. Works with Heroku too!_


#### But why?

Fuck you. That's why.


## Usage

- Download / Clone the script

    ```bash
    git clone https://github.com/sheharyarn/mongo-sync.git
    cd mongo-sync
    ```

- Edit `config.yml` and insert your configuration details

- Use the script like this:
	
	```bash
	./mongo-sync push		# Push DB to Remote
	./mongo-sync pull		# Pull DB from Remote
	```

**Note:** *Pushing/Pulling overwrites the target DB*


## To Do

 - Specify `config.yml` by passing it as an argument
 - More Options for Local DB in `config.yml`


## Contributing

1. [Fork it](https://github.com/sheharyarn/mongo-sync/fork)
2. Create your feature/fix branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request


## License

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

