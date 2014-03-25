# sass2stylus

### Installation
- Install [Ruby](http://ruby-lang.org)
- `gem install sass`
- Install [Node](http://nodejs.org)
- `npm install -g sass2stylus`

### Usage
- `sass2stylus foo.scss`

### API Usage
- `curl -F file=@/your/local/file.scss http://sass2stylus.herokuapp.com > new_file.styl`
- `RestClient.post('http://sass2stylus.herokuapp.com', file: File.open('local_file.scss'))`

### Development
- Clone this repository
- `cd front_end`
- `npm install -g roots`
- `roots compile`
- `ruby app.rb`

---

##### Sass2Stylus is curated by loving hands at...
<a href="http://mojotech.com"><img width="140px" src="https://mojotech.github.io/sass2stylus/img/mojotech-logo.svg" title="MojoTech's Hiring"></a> <sup>(psst, [we're hiring](http://www.mojotech.com/jobs))</sup>