**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:10292] *** Process received signal ***
[runnervm0kj6c:10292] Signal: Aborted (6)
[runnervm0kj6c:10292] Signal code:  (-6)
[runnervm0kj6c:10292] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff20fa45330]
[runnervm0kj6c:10292] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff20fa9eb2c]
[runnervm0kj6c:10292] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff20fa4527e]
[runnervm0kj6c:10292] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff20fa288ff]
[runnervm0kj6c:10292] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff20fea5ff5]
[runnervm0kj6c:10292] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff20febb0da]
[runnervm0kj6c:10292] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff20fea5a55]
[runnervm0kj6c:10292] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff20fea5a6f]
[runnervm0kj6c:10292] [ 8] plumed_master(+0x146dd)[0x5579e3ede6dd]
[runnervm0kj6c:10292] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff20fa2a1ca]
[runnervm0kj6c:10292] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff20fa2a28b]
[runnervm0kj6c:10292] [11] plumed_master(+0x15365)[0x5579e3edf365]
[runnervm0kj6c:10292] *** End of error message ***
</pre>
{% endraw %}
