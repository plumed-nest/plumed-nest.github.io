**Project ID:** [plumID:25.030]({{ '/' | absolute_url }}eggs/25/030/)  
Stderr for source:  plumed_mtd.dat   
Download: [zipped raw stdout](plumed_mtd.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mtd.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:04705] *** Process received signal ***
[runnervm0kj6c:04705] Signal: Aborted (6)
[runnervm0kj6c:04705] Signal code:  (-6)
[runnervm0kj6c:04705] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8383a45330]
[runnervm0kj6c:04705] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8383a9eb2c]
[runnervm0kj6c:04705] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8383a4527e]
[runnervm0kj6c:04705] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8383a288ff]
[runnervm0kj6c:04705] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8383ea5ff5]
[runnervm0kj6c:04705] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8383ebb0da]
[runnervm0kj6c:04705] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8383ea5a55]
[runnervm0kj6c:04705] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8383ea5a6f]
[runnervm0kj6c:04705] [ 8] plumed(+0x146dd)[0x55691dd4b6dd]
[runnervm0kj6c:04705] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8383a2a1ca]
[runnervm0kj6c:04705] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8383a2a28b]
[runnervm0kj6c:04705] [11] plumed(+0x15365)[0x55691dd4c365]
[runnervm0kj6c:04705] *** End of error message ***
</pre>
{% endraw %}
