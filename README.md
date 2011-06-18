Instructions on how to get set-up
=================================
  <code>
  mkdir -p ~/Library/Application\ Support/TextMate/Bundles
  cd ~/Library/Application\ Support/TextMate/Bundles
  git clone git@github.com:jpatzer/Tritium.tmbundle.git 'Tritium.tmbundle'
  osascript -e 'tell app "TextMate" to reload bundles'
  </code>

If you want to make changes to the bundle
=========================================
When you make changes to your Git-ified bundle in the Bundle Editor, you’ll need to Reload Bundles for the changes to show up in your repository. Then you’ll need to git add . and commit / push as you would a normal repository.