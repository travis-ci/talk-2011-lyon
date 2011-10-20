!SLIDE
# How?

!SLIDE bullets center architecture
![architecture](../images/travis.architecture.png)

!SLIDE bullets
# The Worker

!SLIDE workers center
![worker-1](../images/travis.architecture.worker-1.png)

!SLIDE workers center
![worker-2](../images/travis.architecture.worker-2.png)

!SLIDE workers center
![worker-3](../images/travis.architecture.worker-3.png)

!SLIDE workers center
![worker-4](../images/travis.architecture.worker-4.png)

!SLIDE bullets
# The Build
* <span style="color: #c00">Setup</span>
* <span style="color: #00c">Install</span>
* <span style="color: #0c0">Runs Tests</span>

!SLIDE bullets
# A Ruby Build
* <span style="color: #c00">export CI=true</span>
* <span style="color: #c00">git clone && checkout</span>
* <span style="color: #c00">rvm use 1.9.2</span>
* <span style="color: #00c">bundle install</span>
* <span style="color: #0c0">bundle exec rake</span>


