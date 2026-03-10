**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm0kj6c:06156] *** Process received signal ***
[runnervm0kj6c:06156] Signal: Aborted (6)
[runnervm0kj6c:06156] Signal code:  (-6)
[runnervm0kj6c:06156] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f204ae45330]
[runnervm0kj6c:06156] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f204ae9eb2c]
[runnervm0kj6c:06156] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f204ae4527e]
[runnervm0kj6c:06156] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f204ae288ff]
[runnervm0kj6c:06156] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f204b2a5ff5]
[runnervm0kj6c:06156] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f204b2bb0da]
[runnervm0kj6c:06156] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f204b2a5a55]
[runnervm0kj6c:06156] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f204b2a5a6f]
[runnervm0kj6c:06156] [ 8] plumed(+0x146dd)[0x5573012e46dd]
[runnervm0kj6c:06156] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f204ae2a1ca]
[runnervm0kj6c:06156] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f204ae2a28b]
[runnervm0kj6c:06156] [11] plumed(+0x15365)[0x5573012e5365]
[runnervm0kj6c:06156] *** End of error message ***
</pre>
{% endraw %}
