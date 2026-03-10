**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:10233] *** Process received signal ***
[runnervm0kj6c:10233] Signal: Aborted (6)
[runnervm0kj6c:10233] Signal code:  (-6)
[runnervm0kj6c:10233] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd165845330]
[runnervm0kj6c:10233] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd16589eb2c]
[runnervm0kj6c:10233] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd16584527e]
[runnervm0kj6c:10233] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd1658288ff]
[runnervm0kj6c:10233] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd165ca5ff5]
[runnervm0kj6c:10233] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd165cbb0da]
[runnervm0kj6c:10233] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd165ca5a55]
[runnervm0kj6c:10233] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd165ca5a6f]
[runnervm0kj6c:10233] [ 8] plumed_master(+0x146dd)[0x55bac08396dd]
[runnervm0kj6c:10233] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd16582a1ca]
[runnervm0kj6c:10233] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd16582a28b]
[runnervm0kj6c:10233] [11] plumed_master(+0x15365)[0x55bac083a365]
[runnervm0kj6c:10233] *** End of error message ***
</pre>
{% endraw %}
