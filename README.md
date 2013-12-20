# ![«Logo»](https://raw.github.com/jhermann/gitreceive-httpd/master/doc/_static/logo-48.png) gitreceive-httpd

gitreceive hook example that deploys Apache configuration via a push.

## Why?

This project shows how you can use `git` to deploy a website including its configuration
to a remote server running Apache via a simple push from your workdir. It's a showcase for this kind of
`git` usage, and the redux of a real-world project, to get you started quickly with your own.

While you can also use one of the many configuration management tools to do the same, the big advantage
of this method is that it fits naturally into your workflow when you use `git` anyway to
manage your content and configuration.
Also, the immediate feedback you get from the output of the push call is way more convenient
than to have to look into some status reporting website of a configuration management system,
_after_ you waited for it to do its job.

Using a gitreceive hook is thus especially appropriate for frequent small changes, to get them
out rapidly and with ease. It's the way GitHub pages and a lot of cloud deployment tools
operate these days, for the reasons outlined above.


## What?

## How?

### Initial Setup

### Rolling Out a Change

## Details

### Cascading deployment

## Related Projects

 * https://github.com/progrium/gitreceive
 * https://github.com/coreos/go-gitreceive
 * https://github.com/flynn/gitreceive-next
