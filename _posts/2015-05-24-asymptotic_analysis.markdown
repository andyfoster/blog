---
layout: post
title:  "Asymptotic Analysis"
date:   2015-05-25 01:15:37
categories: algorithms
---
#Asymptotic Analysis

Charactersie *time* and *space* complexity

Time complexity
* time for algorithm to complete
* calculate time as function _t(n)_ realting the number of steps to problem instance size _n_

Space complexity
* temporary computer storage
* determine required _s(n)_

##Algorithm Cost
* There is a constant cost to any operation
    - Enbles using _t(n)_ to estimate executiion time
* From algorithm description one can determine total number of steps based on _n_ 

Example

    for d in numnbers:
        sum = sum + d

Time complexity: _t(n) is directly proportional to _n_

The algorithm uses _n_ addition operations regardless of how much data is stored

## Asymptotic Groweh
*Important*

How does the performacne go as the problem gets larger and larger

Evaluate 

The law of small numnbers - the laws that apply to small numbers don't apply to large sets of data

Evaluate _t(n)_ as problem size _n_ doubles
* The true measure for understanding performacne
* Goal is to determine *order of growth* of O(f(n))
* A formal treatment of O(f(n)) can be found in textbooks

