#!/usr/bin/env groovy

docker_oraclejdk8 {
    withPush = true
    dockerRegistry = '368821881613.dkr.ecr.us-west-2.amazonaws.com/'
    dockerRepos = ['confluentinc/kafka-streams-examples']
    slackChannel = '#streams-team'
    upstreamProjects = 'confluentinc/common'
}