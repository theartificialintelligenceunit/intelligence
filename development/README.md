
<br>

### Notes

Launch an interactive environment via

```shell
docker run --rm -i -t -p 8080:80 -w /app 
  --mount type=bind,src="$(pwd)",target=/app 
    dynamic
```

Subsequently, launch a web server via

```shell
nginx -g 'daemon off;'
```

The URL is

```yaml
http://localhost:8080
```

Note, for an immediate web server launch $\rightarrow$

```shell
docker run --rm -i -t -p 8080:80 -w /app 
  --mount type=bind,src="$(pwd)",target=/app 
    dynamic nginx -g 'daemon off;'
```


<br>
<br>

### Snippet

| Sentence #    | Word           | POS  | Tag   |
|:--------------|:---------------|:-----|:------|
| Sentence: 461 | The            | DT   | O     |
| &nbsp;        | report         | NN   | O     |
| &nbsp;        | said           | VBD  | O     |
| &nbsp;        | the            | DT   | O     |
| &nbsp;        | ancient        | JJ   | O     |
| &nbsp;        | communities    | NNS  | O     |
| &nbsp;        | were           | VBD  | O     |
| &nbsp;        | discovered     | VBN  | O     |
| &nbsp;        | in             | IN   | O     |
| &nbsp;        | the            | DT   | O     |
| &nbsp;        | northern       | JJ   | O     |
| &nbsp;        | part           | NN   | O     |
| &nbsp;        | of             | IN   | O     |
| &nbsp;        | Shaanxi        | NNP  | B-geo |
| &nbsp;        | province       | NN   | O     |
| &nbsp;        | ,              | ,    | O     |
| &nbsp;        | a              | DT   | O     |
| &nbsp;        | region         | NN   | O     |
| &nbsp;        | known          | VBN  | O     |
| &nbsp;        | for            | IN   | O     |
| &nbsp;        | its            | PRP$ | O     |
| &nbsp;        | archaeological | JJ   | O     |
| &nbsp;        | treasures      | NNS  | O     |
| &nbsp;        | 0              | 0    | O     |
| Sentence: 462 | Xinhua         | NNP  | B-org |
| &nbsp;        | says           | VBZ  | O     |
| &nbsp;        | the            | DT   | O     |
| &nbsp;        | ruins          | NNS  | O     |
| &nbsp;        | show           | VBP  | O     |

<br>
<br>


### References

live server
* [live server](https://itnext.io/dockerizing-modern-web-apps-cd9667eebf44)
* [github](https://github.com/tapio/live-server)
* [npm](https://www.npmjs.com/package/live-server)

NGINX
* [docker hub](https://hub.docker.com/_/nginx)
* [docker nginx](https://toxigon.com/setting-up-nginx-with-docker)
* [docker nginx](https://www.uptimia.com/questions/how-to-run-nginx-in-the-foreground-within-a-docker-container#implementing-the-solution-in-docker)
* [extra help](https://itnext.io/dockerizing-modern-web-apps-cd9667eebf44)
* [more](https://www.socketxp.com/iot/remote-access-nginx-web-server-from-internet/)
* [nginx -g 'daemon off;'](https://www.thecoderscamp.com/nginx-g-daemon-off/)
* [Dockerfile](https://github.com/devasthali-os/nginx-base/blob/master/Dockerfile)
* [conf](https://nginx.org/en/docs/beginners_guide.html#conf_structure)
* [MIME (Multipurpose Internet Mail Extensions) Types](https://server.hk/blog/14461/)
* [MIME Types](https://www.slingacademy.com/article/nginx-mime-types-the-complete-guide/)
* [load error example](https://www.slingacademy.com/article/nginx-error-cannot-load-css-js-files/)

vim & vi
* [vi](https://linuxsimply.com/cheat-sheets/vi/)
* [vim](https://vim.rtorr.com)
* [vim](https://www.redhat.com/en/blog/beginners-guide-vim)

JavaScript Modules
* [Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
* [Modules](https://javascript.info/modules)
* [Module Errors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/import_decl_module_top_level#importing_in_a_non-module_script)
* [SCRIPT](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script)

<br>
<br>

<br>
<br>

<br>
<br>

<br>
<br>
