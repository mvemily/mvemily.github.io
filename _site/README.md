This file will eventually contain instructions about how to
modify and deploy Emily's campaign website.

We're planning to use the jekyll theme 'agency'
https://github.com/raviriley/agency-jekyll-theme



# Running Jekyll locally


## Use a Ruby Version Manager
Using a Ruby version manager like `rbenv` or `rvm` allows you to manage Ruby versions and gem installations without requiring superuser permissions.

### Using `rbenv`
1. **Install `rbenv`**:
   - On macOS, you can use Homebrew:

     ```sh
     brew install rbenv
     ```

   - Add `rbenv` to your shell:

     ```sh
     echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.zshrc
     source ~/.zshrc
     ```

2. **Install Ruby**:
   - Install a specific version of Ruby:

     ```sh
     rbenv install 3.3.1
     rbenv global 3.3.1
     ```
3. **Set Ruby as active on shell launch**
  - Run this to add to your bash/zsh file:
  
  `if [ "$SHELL" = "/bin/zsh" ]; then echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.zshrc; elif [ "$SHELL" = "/bin/bash" ]; then echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bashrc; fi`

  - Restart your terminal, and run `ruby -v` to make sure you're on ruby 3.3.1

4. **Install Bundler**:
   - Now, install Bundler:

     ```sh
     gem install bundler
     ```

5. Run locally

   ```sh
   bundle install
   bundle exec jekyll serve
   ```
