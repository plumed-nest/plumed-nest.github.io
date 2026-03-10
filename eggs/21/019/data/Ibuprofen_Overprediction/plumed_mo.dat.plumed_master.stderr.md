**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervm0kj6c:09644] *** Process received signal ***
[runnervm0kj6c:09644] Signal: Aborted (6)
[runnervm0kj6c:09644] Signal code:  (-6)
[runnervm0kj6c:09644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb485e45330]
[runnervm0kj6c:09644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb485e9eb2c]
[runnervm0kj6c:09644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb485e4527e]
[runnervm0kj6c:09644] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb485e288ff]
[runnervm0kj6c:09644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4862a5ff5]
[runnervm0kj6c:09644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4862bb0da]
[runnervm0kj6c:09644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4862a5a55]
[runnervm0kj6c:09644] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4862a5a6f]
[runnervm0kj6c:09644] [ 8] plumed_master(+0x146dd)[0x55c22b6d56dd]
[runnervm0kj6c:09644] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb485e2a1ca]
[runnervm0kj6c:09644] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb485e2a28b]
[runnervm0kj6c:09644] [11] plumed_master(+0x15365)[0x55c22b6d6365]
[runnervm0kj6c:09644] *** End of error message ***
</pre>
{% endraw %}
