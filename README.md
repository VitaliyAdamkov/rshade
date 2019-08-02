# RShade  
  
 
![warcraft shade](https://github.com/gingray/rshade/raw/master/shade.jpg)

Ruby Shade or RShade gem to help you to reveal which code are used in program execution.

  
```ruby
trace = RShade::Trace.new  
trace.reveal do  
  #your code here
end
trace.show
#rspec
 rshade_reveal do
   #code here
 end 

```
Below is example how output will looks like.
As you can sse all code that have been using are printed.
[![asciicast](https://asciinema.org/a/MR5KL7TmHmYRUhwBUWQjBI373.svg)](https://asciinema.org/a/MR5KL7TmHmYRUhwBUWQjBI373)

## Installation  
  
Add this line to your application's Gemfile:  
  
```ruby  
gem 'rshade'  
```  
  
And then execute:  
  
 $ bundle  
Or install it yourself as:  
  
 $ gem install rshade  
## Usage  
  
TODO: Write usage instructions here  
  
## TODO  
Use stack to keep connections between current method and caller  
take a look on https://github.com/matugm/visual-call-graph  
  
## Contributing  
  
Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/rshade.  
  
## License  
  
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
