# Initial installation

## Install Hugo with Chocolatey
`choco install hugo -confirm`

## Create a new site
`hugo new site blog`

## Add theme as git submodule
`cd blog`
`git submodule add https://github.com/huyb1991/hugo-lamp themes/hugo-lamp`

## Load submodule when already added
`git submodule update --init --recursive`

## Edit config.toml to define the hugo-lamp theme
`theme = "hugo-lamp"`

## Build and start server
`hugo server -D`



# Using [starter theme](https://themes.gohugo.io/hugo-starter/)
`git submodule add https://github.com/jimfrenette/hugo-starter.git themes/starter`



# Usage

## Create new posts
`hugo new posts/my-first-post.md`


# Deployment

## Using Azure DevOps
See: https://blog.headforcloud.com/2018/12/11/hugo-devops-deploy/


# Customization

## Theme details
See: https://github.com/josephhutch/aether