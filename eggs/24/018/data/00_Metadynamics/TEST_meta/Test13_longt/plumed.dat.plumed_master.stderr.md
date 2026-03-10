**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:07016] *** Process received signal ***
[runnervm0kj6c:07016] Signal: Aborted (6)
[runnervm0kj6c:07016] Signal code:  (-6)
[runnervm0kj6c:07016] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0932045330]
[runnervm0kj6c:07016] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f093209eb2c]
[runnervm0kj6c:07016] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f093204527e]
[runnervm0kj6c:07016] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09320288ff]
[runnervm0kj6c:07016] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09324a5ff5]
[runnervm0kj6c:07016] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09324bb0da]
[runnervm0kj6c:07016] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09324a5a55]
[runnervm0kj6c:07016] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09324a5a6f]
[runnervm0kj6c:07016] [ 8] plumed_master(+0x146dd)[0x56037f46f6dd]
[runnervm0kj6c:07016] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f093202a1ca]
[runnervm0kj6c:07016] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f093202a28b]
[runnervm0kj6c:07016] [11] plumed_master(+0x15365)[0x56037f470365]
[runnervm0kj6c:07016] *** End of error message ***
</pre>
{% endraw %}
