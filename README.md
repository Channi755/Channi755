- 👋 Hi, I’m @Channi755
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Channi755/Channi755 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes
This site can’t be reached102.103.7.5 took too long to respond.
true nas
Error: Traceback (most recent call last):
  File "/usr/local/lib/python3.9/site-packages/middlewared/job.py", line 355, in run
    await self.future
  File "/usr/local/lib/python3.9/site-packages/middlewared/job.py", line 393, in __run_body
    rv = await self.middleware.run_in_thread(self.method, *([self] + args))
  File "/usr/local/lib/python3.9/site-packages/middlewared/main.py", line 1154, in run_in_thread
    return await self.run_in_executor(self.thread_pool_executor, method, *args, **kwargs)
  File "/usr/local/lib/python3.9/site-packages/middlewared/main.py", line 1151, in run_in_executor
    return await loop.run_in_executor(pool, functools.partial(method, *args, **kwargs))
  File "/usr/local/lib/python3.9/concurrent/futures/thread.py", line 58, in run
    result = self.fn(*self.args, **self.kwargs)
  File "/usr/local/lib/python3.9/site-packages/middlewared/schema.py", line 979, in nf
    return f(*args, **kwargs)
  File "/usr/local/lib/python3.9/site-packages/middlewared/plugins/jail_freebsd.py", line 372, in available
    return self.middleware.call_sync('plugin.available_impl', options).wait_sync(raise_error=True)
  File "/usr/local/lib/python3.9/site-packages/middlewared/job.py", line 326, in wait_sync
    raise CallError(self.error)
middlewared.service_exception.CallError: [EFAULT] Cmd('git') failed due to: exit code(128)
  cmdline: git clone -v https://github.com/freenas/iocage-ix-plugins.git /mnt/My Nas/iocage/.plugins/github_com_freenas_iocage-ix-plugins_git
  stderr: 'Cloning into '/mnt/My Nas/iocage/.plugins/github_com_freenas_iocage-ix-plugins_git'...
fatal: unable to access 'https://github.com/freenas/iocage-ix-plugins.git/': Could not resolve host: github.com
'
