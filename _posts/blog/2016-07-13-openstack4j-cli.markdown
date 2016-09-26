---
layout: post
title:  "Openstack 4j CLI"
date:   2016-07-13 16:54:46
author: Vinod Borole
categories: 
- blog
- Openstack
- Development
- Openstack4j
- CLI
img: o4j-shell.jpg
thumb: thumb02.jpg
---

This project was started with a thought of having an easy automation tool to interact with Openstack. Considering the challenges one has with existing Openstack CLI, this tool offers a very good starting point in overcoming those challenges. <!--more-->

#### Setup
Unlike the existing Openstack CLI, this tool does not require any pre-requisite software to be installed. Openstack4j CLI is completely written in Java and consumes the API from openstack4j library; to run, it just needs JRE 6+ installed which in most operating systems is by default available. It comprises of a single executable jar that is portable on any Java or OS platform.

#### All-in-one
It’s an all in one solution - Single client for all the Openstack services. Openstack4j CLI is all in one, it bundles all primary Openstack service clients into one; mainly glance, nova, neutron, cinder etc.

#### Easy to use
Fluent CLI's, easy to use and understand CLI commands to do precisely what is needed. With Fluent and easy to understand commands, it takes care of dependent resource creation for the particular cases where resources from other Openstack services (neutron, cinder) are needed that encourages automation and abstracts out unnecessary complexity from user so that he can focus on intent of operation.

#### Smart
Inbuilt memory feature that remembers the output of the command. Openstack4j CLI comes with an inbuilt memory feature, that saves all the resource Ids generated from previously executed command and automatically replaces the values in subsequent command as and when needed.

More Info: http://vinodborole.github.io/openstack4j-shell/
