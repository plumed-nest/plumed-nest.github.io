**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:06183] *** Process received signal ***
[runnervm0kj6c:06183] Signal: Aborted (6)
[runnervm0kj6c:06183] Signal code:  (-6)
[runnervm0kj6c:06183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab32a45330]
[runnervm0kj6c:06183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab32a9eb2c]
[runnervm0kj6c:06183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab32a4527e]
[runnervm0kj6c:06183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab32a288ff]
[runnervm0kj6c:06183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab32ea5ff5]
[runnervm0kj6c:06183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab32ebb0da]
[runnervm0kj6c:06183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab32ea5a55]
[runnervm0kj6c:06183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab32ea5a6f]
[runnervm0kj6c:06183] [ 8] plumed_master(+0x146dd)[0x56012b41f6dd]
[runnervm0kj6c:06183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab32a2a1ca]
[runnervm0kj6c:06183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab32a2a28b]
[runnervm0kj6c:06183] [11] plumed_master(+0x15365)[0x56012b420365]
[runnervm0kj6c:06183] *** End of error message ***
</pre>
{% endraw %}
