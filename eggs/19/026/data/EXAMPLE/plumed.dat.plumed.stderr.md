**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervm0kj6c:12788] *** Process received signal ***
[runnervm0kj6c:12788] Signal: Aborted (6)
[runnervm0kj6c:12788] Signal code:  (-6)
[runnervm0kj6c:12788] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc410445330]
[runnervm0kj6c:12788] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc41049eb2c]
[runnervm0kj6c:12788] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc41044527e]
[runnervm0kj6c:12788] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4104288ff]
[runnervm0kj6c:12788] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4108a5ff5]
[runnervm0kj6c:12788] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4108bb0da]
[runnervm0kj6c:12788] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4108a5a55]
[runnervm0kj6c:12788] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4108a5a6f]
[runnervm0kj6c:12788] [ 8] plumed(+0x146dd)[0x55eec07f26dd]
[runnervm0kj6c:12788] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc41042a1ca]
[runnervm0kj6c:12788] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc41042a28b]
[runnervm0kj6c:12788] [11] plumed(+0x15365)[0x55eec07f3365]
[runnervm0kj6c:12788] *** End of error message ***
</pre>
{% endraw %}
