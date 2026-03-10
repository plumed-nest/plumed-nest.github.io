**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervm0kj6c:04146] *** Process received signal ***
[runnervm0kj6c:04146] Signal: Aborted (6)
[runnervm0kj6c:04146] Signal code:  (-6)
[runnervm0kj6c:04146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb858845330]
[runnervm0kj6c:04146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb85889eb2c]
[runnervm0kj6c:04146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb85884527e]
[runnervm0kj6c:04146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8588288ff]
[runnervm0kj6c:04146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb858ca5ff5]
[runnervm0kj6c:04146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb858cbb0da]
[runnervm0kj6c:04146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb858ca5a55]
[runnervm0kj6c:04146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb858ca5a6f]
[runnervm0kj6c:04146] [ 8] plumed_master(+0x146dd)[0x5604887a76dd]
[runnervm0kj6c:04146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb85882a1ca]
[runnervm0kj6c:04146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb85882a28b]
[runnervm0kj6c:04146] [11] plumed_master(+0x15365)[0x5604887a8365]
[runnervm0kj6c:04146] *** End of error message ***
</pre>
{% endraw %}
