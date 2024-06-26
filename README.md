# Articles

## WebAssembly
- wasi https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/
- cloud-computing-without-containers https://blog.cloudflare.com/cloud-computing-without-containers/
- running-nginx-with-webassembly https://syrusakbary.medium.com/running-nginx-with-webassembly-6353c02c08ac

## golang
- Scalable Go Scheduler Design Doc https://docs.google.com/document/d/1TTj4T2JO42uD5ID9e89oa0sLKhJYD0Y_kqxDv3I3XMw
- Goroutine and Preemption https://medium.com/a-journey-with-go/go-goroutine-and-preemption-d6bc2aa2f4b7
- Asynchronous Preemption https://medium.com/a-journey-with-go/go-asynchronous-preemption-b5194227371c
- gsignal, Master of Signals https://medium.com/a-journey-with-go/go-gsignal-master-of-signals-329f7ff39391
- go-scheduler https://morsmachine.dk/go-scheduler
- The Go netpoller https://morsmachine.dk/netpoller
- gotchas-and-common-mistakes-in-go-golang http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/
- golang http timeout https://blog.cloudflare.com/the-complete-guide-to-golang-net-http-timeouts/
- golangs-real-time-gc-in-theory-and-practice https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/
- low-latency-gc https://blog.twitch.tv/gos-march-to-low-latency-gc-a6fa96f06eb7
- The Journey of Go's Garbage Collector https://blog.golang.org/ismmkeynote
- 字节跳动在 Go 网络库上的实践 https://www.infoq.cn/article/fea7chf9moohbxbtyres
- 高性能队列 disruptor https://lmax-exchange.github.io/disruptor/disruptor.html

## rust
- non-lexical-lifetimes http://smallcultfollowing.com/babysteps/blog/2016/04/27/non-lexical-lifetimes-introduction/
- Futures Explained in 200 Lines of Rust https://cfsamson.github.io/books-futures-explained/
- http://smallcultfollowing.com/babysteps/
- https://boats.gitlab.io/blog/ 
- io-uring https://boats.gitlab.io/blog/post/io-uring/
- https://seanmonstar.com/
- dynamic-dispatch-in-rust https://alschwalm.com/blog/static/2017/03/07/exploring-dynamic-dispatch-in-rust/
- How Rust optimizes async/await https://tmandry.gitlab.io/blog/posts/optimizing-await-1/
- Async interviews https://smallcultfollowing.com/babysteps/blog/2019/11/22/announcing-the-async-interviews/
- https://this-week-in-rust.org/
- rust-error-handling https://nick.groenen.me/posts/rust-error-handling/
- rust-compilation https://pingcap.com/blog/rust-compilation-model-calamity/
- generics-and-compile-time https://pingcap.com/blog/generics-and-compile-time-in-rust/
- https://nnethercote.github.io/perf-book/
- 40-ms-bug https://vorner.github.io/2020/11/06/40-ms-bug.html
- rust-pin-unpin https://folyd.com/blog/rust-pin-unpin/
- delete-cargo-integration-tests https://matklad.github.io/2021/02/27/delete-cargo-integration-tests.html
- zero abstraction https://blog.rust-lang.org/2015/05/11/traits.html
- rust-blog https://github.com/pretzelhammer/rust-blog
- why async fn in traits are hard http://smallcultfollowing.com/babysteps/blog/2019/10/26/async-fn-in-traits-are-hard/
- how-async-functions-in-traits-could-work-in-rustc https://blog.theincredibleholk.org/blog/2022/04/18/how-async-functions-in-traits-could-work-in-rustc/

## container
- docker network http://blog.oddbit.com/2014/08/11/four-ways-to-connect-a-docker/
- namespaces https://lwn.net/Articles/531114/#series_index
- microcontainer https://blogs.oracle.com/developers/the-microcontainer-manifesto
- https://iximiuz.com/en/posts/kubernetes-ephemeral-containers/

## network 
- deep-dive-into-iptables https://www.digitalocean.com/community/tutorials/a-deep-dive-into-iptables-and-netfilter-architecture
- ip route fundamental 
  - https://www.thegeekstuff.com/2012/04/ip-routing-intro/
  - https://www.thegeekstuff.com/2012/04/route-examples/
  - https://www.thegeekstuff.com/2012/05/route-flags/
- how-vxlan-works-on-linux https://www.slideshare.net/enakai/how-vxlan-works-on-linux
- how-vxlan-works-on-l2-and-across-l3-networks https://www.slideshare.net/anandnande/how-vxlan-works-on-l2-and-across-l3-networks
- build dns guide https://github.com/EmilHernvall/dnsguide
- https://arthurchiao.art/blog/conntrack-design-and-implementation-zh

## service discovery
- shouldnt-use-zookeeper-for-service-discovery https://medium.com/knerd/eureka-why-you-shouldnt-use-zookeeper-for-service-discovery-4932c5c7e764

## raft
raft dissertation https://github.com/ongardie/dissertation

## system admin
https://github.com/trimstray/test-your-sysadmin-skills

## Concurrency is not parallelism
- async basic https://cfsamson.github.io/book-exploring-async-basics/
- epoll-vs-kqueue http://web.archive.org/web/20190112082733/https://people.eecs.berkeley.edu/~sangjin/2012/12/21/epoll-vs-kqueue.html
- green thread https://cfsamson.gitbook.io/green-threads-explained-in-200-lines-of-rust/
- reactor-pattern https://tianpan.co/blog/2015-01-13-understanding-reactor-pattern-for-highly-scalable-i-o-bound-web-server
- Futures Explained in 200 Lines of Rust https://cfsamson.github.io/books-futures-explained/introduction.html
- The Waker API I: what does a waker do? https://boats.gitlab.io/blog/post/wakers-i/
- How Rust optimizes async/await https://tmandry.gitlab.io/blog/posts/optimizing-await-1/
- Epoll, Kqueue and IOCP Explained with Rust https://cfsamsonbooks.gitbook.io/epoll-kqueue-iocp-explained/
- tokio scheduler https://tokio.rs/blog/2019-10-scheduler
- https://stjepang.github.io/2020/01/31/build-your-own-executor.html
- https://stjepang.github.io/2020/01/25/build-your-own-block-on.html

## io-uring
- lwn io-uring articles https://lwn.net/Kernel/Index/#io_uring

## quic 
- http3-and-quic https://www.fastly.com/blog/modernizing-the-internet-with-http3-and-quic

## other 
- oauth-2 https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2
- Interview-Notebook https://github.com/CyC2018/Interview-Notebook
- linux-network-performance-parameters https://github.com/leandromoreira/linux-network-performance-parameters
- https://www.slideshare.net/brendangregg/how-netflix-tunes-ec2-instances-for-performance
- https://www.thesslstore.com/blog/explaining-ssl-handshake/
- https://cvvz.github.io/post/k8s-3-deletion-webhook/ 
- practical dod https://vimeo.com/649009599
- https://arthurchiao.art/blog/cracking-k8s-node-proxy/
- https://arthurchiao.art/blog/socket-acceleration-with-ebpf-zh/
- https://arthurchiao.art/blog/understanding-ebpf-datapath-in-cilium-zh/
