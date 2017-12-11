Notebooks repository for Rock The JVM with Scala course on Udemy.

### Booting the Notebooks Container (Docker Users)

After installing docker and you started it, all you need to do is:

```bash
cd <path/to/this/project>
docker-compose up
```

Now wait a few seconds for the container to boot until you will see some logs telling you how to access it:

```text
notebook_1  |     Copy/paste this URL into your browser when you connect for the first time,
notebook_1  |     to login with a token:
notebook_1  |         http://0.0.0.0:8080/?token=7e3690fdfeb94279e347706cd3535407695e8e9e8e03543d
```

Simply copy the link and paste it in your browser. If `0.0.0.0` doesn't work, try replacing it with either `localhost` or `127.0.0.1` (I've seen different variants working on different operating systems - `localhost` should work anywhere though).

Congratulations, that's it!

### Running Notebooks

If you're using Docker, all the notebooks are available within the container itself so you can jump over this section. If you're not able to use the provided Docker container, you can import all the notebooks that are found in this repository under the path `/notebooks` directly in Jupyter. How to do this:

1. First, start the jupyter server (varies depending on your OS)
2. Once you open jupyter in your browser look for the `Upload` button in the right upper side. Click on it, then select and upload the notebooks from this repository in it.

Cool, that's it, you're now able to run the notebooks!

I recommend starting off with `Notebooks 101` and then following the same order as in the course:
1. Values, Variables & Types
2. Expressions
3. Functions
4. Recursion
5. Smart Strings
6. CBN vs. CBV

Note - the notebooks will probably be re-arranged in a logical and ordered and the storage format will slightly be improved so additional steps might appear here to workaround those issues - for now it should do its job though.

Enjoy!
