# chef-elixir (v0.1) #

a chef recipe for elixir

## usage ##

### installing elixir ###

include `recipe[elixir]` in your `run_list`

the following attributes are available to override:

* `elixir_git_url`
  the url of the git repo to clone elixir from
* `elixir_git_ref`
  the git reference to checkout from the elixir git repo
* `otp_git_url`
  the url of the git repo to clone erlang from
* `otp_git_ref`
  the git reference to checkout from the otp git repo
* `config_flags`
  a list of flags to pass to the configure script for the erlang runtime

## license ##

The MIT License (MIT)

Copyright (c) 2013 alisdair sullivan <alisdairsullivan@yahoo.ca>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.