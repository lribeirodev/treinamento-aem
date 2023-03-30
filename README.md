# AEM NINJA TRAINING

This training is focused on development frontend and backend with AEM

</br>

# FIGMA

https://www.figma.com/file/H1z08MqopioTW4LmwVtChj/O-TEMPO-TEMPLATE-BASICO?node-id=0%3A1&t=jo7hCbguEPcYYIBz-1

</br>

# THREE COMPONENTS MUST BE DEVELOPED

<p>HEADER</p>
<p>LAST NEWS</p>
<p>COLUMNIST</p>

<p>ONE TEMPLATE MUST BE DEVELOP USING THE HEADER COMPONENT</p>

</br>

# STEPS TO INITIATE

fork from the repo to your account</br>
before git clone, execute the following command in terminal as a administrator</br>
git config --system core.longpaths true</br>
after this, git clone of the project</br>
and build 

# SET UP YOUR LOCAL BRANCH TO UPDATE FROM REMOTE BRANCH
git remote add upstream https://github.com/aemninjadev/treinamento-aem.git</br>
git checkout master</br>
git pull upstream master</br>
git push origin master</br>


# HOW TO BUILD THE PROJECT

<b>IN ROOT PATH OF THE PROJECT</b></br>
```
mvn clean install -PautoInstallPackage,autoInstallBundle
```

<b>IN THE FRONTEND MODULE WE HAVE TWO SCRIPTS</b></br>

```
npm run deploy-local --> to deploy all the modules
```

```
npm run deploy-bundle --> to deploy only de java module
```

# GITFLOW

create your branch always from master</br>
with a name that make sense for example</br>

<b>Update your local branch first</b></br>
git checkout master</br>
git pull upstream master</br>
git push origin master</br>

<b>Now create your branch from master</b></br>
git checkout -b feature/component/master</br>