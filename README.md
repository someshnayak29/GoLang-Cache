GoLang LRU Cache

This is a simple LRU (Least Recently Used) cache implementation in GoLang.

Overview

LRU Cache is a data structure that holds a fixed number of items and evicts the least recently used item when the cache reaches its limit.

Features
LRU Eviction: Automatically removes the least recently used item when the cache reaches its capacity.
Thread-Safe: Uses mutex locks to ensure safe concurrent access.
Customizable Capacity: Easily adjust the maximum number of items the cache can hold.

Installation

To use this package, you need to have Go installed and configured. Then, you can install the package using go get:

go get github.com/someshnayak29/golang-lru-cache

