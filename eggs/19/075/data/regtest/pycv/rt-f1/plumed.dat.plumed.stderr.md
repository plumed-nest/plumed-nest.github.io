**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervm0kj6c:10375] *** Process received signal ***
[runnervm0kj6c:10375] Signal: Aborted (6)
[runnervm0kj6c:10375] Signal code:  (-6)
[runnervm0kj6c:10375] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5338445330]
[runnervm0kj6c:10375] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f533849eb2c]
[runnervm0kj6c:10375] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f533844527e]
[runnervm0kj6c:10375] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53384288ff]
[runnervm0kj6c:10375] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53388a5ff5]
[runnervm0kj6c:10375] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53388bb0da]
[runnervm0kj6c:10375] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53388a5a55]
[runnervm0kj6c:10375] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53388a5a6f]
[runnervm0kj6c:10375] [ 8] plumed(+0x146dd)[0x5621fbb616dd]
[runnervm0kj6c:10375] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f533842a1ca]
[runnervm0kj6c:10375] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f533842a28b]
[runnervm0kj6c:10375] [11] plumed(+0x15365)[0x5621fbb62365]
[runnervm0kj6c:10375] *** End of error message ***
</pre>
{% endraw %}
