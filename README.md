# OTP CheatSheet
Every OTP behavior has main parts in its API: client, server, possible inputs and possible outputs. But a one-dimensional structure of standard documentation (from top to bottom) can't present all these parts in one place which leads to loss of a context and longer learn-curve. 

This cheat sheet is an attempt to present common parts of OTP behaviors in one place using opportunities of a two-dimensional structure.

## Table of Contents
- [Supervisor](#supervisor)
  - [Init](#init)
- [Gen Server](#gen-server)
  - [Init](#init-1)
  - [Sync operation](#sync-operation)
  - [Async operation](#async-operation)
  - [Info message](#info-message)
  - [Terminate](#terminate)
- [Contributing](#contributing)

## Supervisor

#### Init
<img src="https://rawgit.com/Telichkin/otp_cheatsheet/master/pictures/supervisor_init.svg" width="100%">

## Gen Server

#### Init
<img src="https://rawgit.com/Telichkin/otp_cheatsheet/master/pictures/gen_server_init.svg" width="100%">

#### Sync operation 
<img src="https://rawgit.com/Telichkin/otp_cheatsheet/master/pictures/gen_server_call.svg" width="100%">

#### Async operation
<img src="https://rawgit.com/Telichkin/otp_cheatsheet/master/pictures/gen_server_cast.svg" width="100%">

#### Info message
<img src="https://rawgit.com/Telichkin/otp_cheatsheet/master/pictures/gen_server_info.svg" width="100%">

#### Terminate
<img src="https://rawgit.com/Telichkin/otp_cheatsheet/master/pictures/gen_server_terminate.svg" width="100%">

## Contributing
1. Fork it (https://github.com/Telichkin/otp_cheatsheet/fork)
2. Open and edit CheatSheet.html in the [draw.io](https://draw.io)
3. Export edited images as SVG into your repository using settings below:
<img src="https://rawgit.com/Telichkin/otp_cheatsheet/master/pictures/svg_settings.png">
4. Create a new Pull Request
