<h1 align="center">Hi there 👋, I'm Jared.</h1>
<h3 align="center">:pizza: P I Z Z A is life</h3>

<p align="center">
  <a href="https://badges.pufler.dev">
    <img src="https://badges.pufler.dev/years/codeimpossible?style=flat&labelColor=333333&logoColor=E7E7E7&color=0089FF&label=Years&logo=github" />
  </a>
  <a href="https://hits.seeyoufarm.com">
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fcodeimpossible&count_bg=%2379C83D&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false" />
  </a>
  <a href="https://twitter.com/codeimpossible" target="blank">
    <img src="https://img.shields.io/badge/Follow-@codeimpossible-FF0069?style=flat&labelColor=333333&logoColor=E7E7E7&logo=twitter" />
  </a>
</p>

```ruby
class Meatbag
  def initialize()
    h = yield(self) if block_given?
	  h.each do |key, value|
	    instance_eval { class << self; self end }.send(:attr_accessor, key)
      self.instance_variable_set("@#{key}".to_sym, value)
	  end
  end
end

def main
  @me = Meatbag.new do |m|
    {
      :name => "Jared",
      :username => "codeimpossible",
      :pronouns => "they/them",
      :location => "Boston, MA",
      :blog => "http://jaredbarboza.me",
      :hobbies => [:coding, :gaming, :film],
      
      # working on a game called Electric Noir
      :interests => [:programming, :gamedevelopment, :opensource],
      :is_active => true
    }
  end
end
```

Languages 💾
------------
[![C#](      https://img.shields.io/badge/-.net-333333?style=for-the-badge&logo=dotnet&logoColor=white&labelColor=2C39BD          )](https://www.dot.net/)
[![JavaScript](      https://img.shields.io/badge/-JS-333333?style=for-the-badge&logo=javascript&logoColor=white&labelColor=DD3A0A         )](https://www.javascript.com/)
[![Ruby](   https://img.shields.io/badge/-Ruby-333333?style=for-the-badge&logo=ruby&logoColor=white&labelColor=DF9100    )](https://www.ruby-lang.org/en/)
[![Python](   https://img.shields.io/badge/-Python-333333?style=for-the-badge&logo=python&logoColor=white&labelColor=3776FB    )](https://www.python.org/)
[![C++](      https://img.shields.io/badge/-C++-333333?style=for-the-badge&logo=c%2B%2B&logoColor=white&labelColor=00599C      )](https://isocpp.org/)

