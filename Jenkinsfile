import hudson.plugins.git.extensions.impl.CleanCheckout
node {
  scm.extensions.replace(new CleanCheckout())
  checkout scm
}
