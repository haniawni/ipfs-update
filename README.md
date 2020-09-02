你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# ipfs-update

> An updater tool for ipfs. Can fetch and install given versions of go-ipfs.

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](http://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![Travis CI](https://travis-ci.org/ipfs/ipfs-update.svg?branch=master)](https://travis-ci.org/ipfs/ipfs-update)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Install

Requirement: Go version 1.8 or higher.

```sh
go get -u github.com/ipfs/ipfs-update
```
Note that your $GOPATH/bin should be within $PATH for the result ipfs-update binary to be found.

## Usage

If you do not see the expected version listed by `ipfs-update versions`. Try updating
`ipfs-update` (either by the above `go get` command or through gobuilder).

#### version

`$ ipfs-update version`

Prints out the version of ipfs that is currently installed.

#### versions

`$ ipfs-update versions`

Prints out all versions of ipfs available for installation.

#### install

`$ ipfs-update install <version>`

Downloads, tests, and installs the specified version
of ipfs. The existing version is stashed in case a revert is needed.

#### revert

`$ ipfs-update revert`

Reverts to the previously installed version of ipfs. This
is useful if the newly installed version has issues and you would like to switch
back to your older stable installation.

#### fetch

`$ ipfs-update fetch`

Downloads the specified version of ipfs into your current
directory. This is a plumbing command that can be utilized in scripts or by
more advanced users.

## Contribute

Feel free to join in. All welcome. Open an [issue](https://github.com/ipfs/ipfs-update/issues)!

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)

## License

[MIT](LICENSE)

