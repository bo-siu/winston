Winston
=======
> What is Winston?

> Winston is the leading role of the book called '1984'.

## Legend
![Legend](./Winston.png)

Winston provides 3 ways to access Internet:

* Normal Access.
* Shadowsocks Access.
* Tor Access (Because tor is blocked in China, so it is necessary to use shadowsocks as proxy for it).

## How to use

1. First, you should have an available shadowsocks server.
2. Configure shadowsocks configuration (`config/shadowsocks/config.json`) that let it connected to the shadowsocks server.
3. Install [docker-compose](https://docs.docker.com/compose/).
4. Use dokcer-compose to run Winston.
5. After you run winston, you will find localhost:8118 is exposed(Use netstat -ntlp to view it).
6. Use localhost:8118 as your proxy.
7. Enjoy it.

## I always said
> I just want to be a person with all the rights that I should own, including freedom.

