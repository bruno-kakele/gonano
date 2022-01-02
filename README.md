Gonano
======

Gonano is primarily a command-line tool written in Go for creating and managing Nano wallets, with the ability to both send and receive amounts. Gonano also comprises a `wallet` package which handles key management and an `rpc` package for communicating with Nano nodes.

This is a fork from Hector Chu's original project: https://github.com/hectorchu/gonano

Check out their project for a complete README. The goal of this fork is to add some extra functionality, which I plan to merge onto the original project as needed.

Install
-------

    go get github.com/bruno-kakele/gonano@v0.1.17
    
Replace the `0.1.17` with the desired version.

Extra commands
------------------

    gonano list -a

You can specify an account to get the balance from. The account doesn't need to be in the wallets.
