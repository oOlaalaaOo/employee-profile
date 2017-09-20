<template>
  <div id="app">
    <section class="section">
 
      <nav class="navbar is-warning">
        <div class="navbar-brand">

          <a class="navbar-item" href="http://bulma.io">
            <img src="http://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
          </a>

          <a class="navbar-item is-hidden-desktop" href="https://twitter.com/jgthms" target="_blank">
            <span class="icon" style="color: #55acee;">
              <i class="fa fa-lg fa-twitter"></i>
            </span>
          </a>

          <div class="navbar-burger burger" data-target="navMenuTransparentExample">
            <span></span>
            <span></span>
            <span></span>
          </div>

        </div>

        <div id="navMenuTransparentExample" class="navbar-menu is-active">

          <div class="navbar-start">
          
            <a class="navbar-item " href="http://bulma.io/expo/">
              Expo
            </a>

            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link" href="/documentation/overview/start/">
                Docs
              </a>
              <div class="navbar-dropdown is-boxed">
                <a class="navbar-item " href="/documentation/overview/start/">
                  Overview
                </a>
                <a class="navbar-item " href="http://bulma.io/documentation/modifiers/syntax/">
                  Modifiers
                </a>
                <a class="navbar-item " href="http://bulma.io/documentation/columns/basics/">
                  Columns
                </a>
                <a class="navbar-item " href="http://bulma.io/documentation/layout/container/">
                  Layout
                </a>
                <a class="navbar-item " href="http://bulma.io/documentation/form/general/">
                  Form
                </a>
                <a class="navbar-item " href="http://bulma.io/documentation/elements/box/">
                  Elements
                </a>
                
                <a class="navbar-item is-active" href="http://bulma.io/documentation/components/breadcrumb/">
                  Components
                </a>
                
                <hr class="navbar-divider">
                <div class="navbar-item">
                  <div>
                    <p class="is-size-6-desktop">
                      <strong class="has-text-info">0.5.2</strong>
                    </p>
                    
                    <small>
                    <a class="bd-view-all-versions" href="/versions">View all versions</a>
                    </small>
                    
                  </div>
                </div>
              </div>
            </div>

            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link " href="http://bulma.io/blog/">
                Blog
              </a>
              <div id="blogDropdown" class="navbar-dropdown is-boxed" data-style="width: 18rem;">
                
                <a class="navbar-item" href="/2017/08/03/list-of-tags/">
                  <div class="navbar-content">
                    <p>
                      <small class="has-text-info">03 Aug 2017</small>
                    </p>
                    <p>New feature: list of tags</p>
                  </div>
                </a>
                
                <a class="navbar-item" href="/2017/08/01/bulma-bootstrap-comparison/">
                  <div class="navbar-content">
                    <p>
                      <small class="has-text-info">01 Aug 2017</small>
                    </p>
                    <p>Bulma / Bootstrap comparison</p>
                  </div>
                </a>
                
                <a class="navbar-item" href="/2017/07/24/access-previous-bulma-versions/">
                  <div class="navbar-content">
                    <p>
                      <small class="has-text-info">24 Jul 2017</small>
                    </p>
                    <p>Access previous Bulma versions</p>
                  </div>
                </a>
                
                <a class="navbar-item" href="http://bulma.io/blog/">
                  More posts
                </a>
                <hr class="navbar-divider">
                <div class="navbar-item">
                  <div class="navbar-content">
                    <div class="level is-mobile">
                      <div class="level-left">
                        <div class="level-item">
                          <strong>Stay up to date!</strong>
                        </div>
                      </div>
                      <div class="level-right">
                        <div class="level-item">
                          <a class="button bd-is-rss is-small" href="http://bulma.io/atom.xml">
                            <span class="icon is-small">
                              <i class="fa fa-rss"></i>
                            </span>
                            <span>Subscribe</span>
                          </a>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <div class="navbar-end">
            <a class="navbar-item is-hidden-desktop-only" href="https://github.com/jgthms/bulma" target="_blank">
              <span class="icon" style="color: #333;">
                <i class="fa fa-lg fa-github"></i>
              </span>
            </a>

            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link " href="http://bulma.io/blog/">
                Account
              </a>
              <div id="blogDropdown" class="navbar-dropdown is-boxed is-right" data-style="width: 18rem;">
                
                <a class="navbar-item" href="/2017/08/03/list-of-tags/">
                  <div class="navbar-content">
                    <p>
                      <small class="has-text-info">03 Aug 2017</small>
                    </p>
                    <p>New feature: list of tags</p>
                  </div>
                </a>
                
                <a class="navbar-item" href="/2017/08/01/bulma-bootstrap-comparison/">
                  <div class="navbar-content">
                    <p>
                      <small class="has-text-info">01 Aug 2017</small>
                    </p>
                    <p>Bulma / Bootstrap comparison</p>
                  </div>
                </a>
                
                <a class="navbar-item" href="/2017/07/24/access-previous-bulma-versions/">
                  <div class="navbar-content">
                    <p>
                      <small class="has-text-info">24 Jul 2017</small>
                    </p>
                    <p>Access previous Bulma versions</p>
                  </div>
                </a>
                
                <a class="navbar-item" href="http://bulma.io/blog/">
                  More posts
                </a>
                <hr class="navbar-divider">
                <div class="navbar-item">
                  <div class="navbar-content">
                    <div class="level is-mobile">
                      <div class="level-left">
                        <div class="level-item">
                          <strong>Stay up to date!</strong>
                        </div>
                      </div>
                      <div class="level-right">
                        <div class="level-item">
                          <a class="button bd-is-rss is-small" href="http://bulma.io/atom.xml">
                            <span class="icon is-small">
                              <i class="fa fa-logout"></i>
                            </span>
                            <span>Logout</span>
                          </a>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>

        </div>
      </nav>

      <div class="container is-fluid">

          <router-view></router-view>

      </div>

    </section>
    
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
  .section{
    padding: 0 0 0 0;
  }
</style>
