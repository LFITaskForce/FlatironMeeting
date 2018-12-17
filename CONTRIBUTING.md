# Instructions to contribute to the website

The website for the workshop is built using Jekyll and hosted on
GitHub pages.
The main branch is protected, contributions are welcome by pull
requests.

## Locally building the site

Instructions can be found on the GitHub documentation here:
https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

Here is a short summary:

  - Make sure Ruby 2.1.0 or higher is installed and install
   `bundler`:
   ```
   $ gem install bundler
   ```

  - Clone this repository and go to the `docs` folder:
   ```
   $ git clone git@github.com:LFITaskForce/FlatironMeeting.git
   $ cd FlatironMeeting/docs
   ```

  - Install Jekyll and dependencies using:
   ```
   $ bundle install --path ~/.gem
   ```
   (Or adapt this command if you want to install the gems somewhere else)

  - Serve the website with:
   ```
   $ bundle exec jekyll serve
   ```
   This should start a server and make the website accessible at a local address like `http://127.0.0.1:4000/FlatironMeeting/`

And that's it, only type the last step to restart the server the next time around.
