**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervm76f27:06576] *** Process received signal ***
[runnervm76f27:06576] Signal: Aborted (6)
[runnervm76f27:06576] Signal code:  (-6)
[runnervm76f27:06576] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5fe4c45330]
[runnervm76f27:06576] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5fe4c9ec0c]
[runnervm76f27:06576] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5fe4c4527e]
[runnervm76f27:06576] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5fe4c288ff]
[runnervm76f27:06576] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5fe50a5ff5]
[runnervm76f27:06576] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5fe50bb0da]
[runnervm76f27:06576] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5fe50a5a55]
[runnervm76f27:06576] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5fe50a5a6f]
[runnervm76f27:06576] [ 8] plumed(+0x146dd)[0x55a7b1c886dd]
[runnervm76f27:06576] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5fe4c2a1ca]
[runnervm76f27:06576] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5fe4c2a28b]
[runnervm76f27:06576] [11] plumed(+0x15365)[0x55a7b1c89365]
[runnervm76f27:06576] *** End of error message ***
</pre>
{% endraw %}
