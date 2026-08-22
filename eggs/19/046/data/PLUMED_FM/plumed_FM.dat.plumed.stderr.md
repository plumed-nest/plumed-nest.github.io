**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[runnervm76f27:12202] *** Process received signal ***
[runnervm76f27:12202] Signal: Aborted (6)
[runnervm76f27:12202] Signal code:  (-6)
[runnervm76f27:12202] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0068c45330]
[runnervm76f27:12202] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0068c9ec0c]
[runnervm76f27:12202] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0068c4527e]
[runnervm76f27:12202] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0068c288ff]
[runnervm76f27:12202] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f00690a5ff5]
[runnervm76f27:12202] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f00690bb0da]
[runnervm76f27:12202] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f00690a5a55]
[runnervm76f27:12202] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f00690a5a6f]
[runnervm76f27:12202] [ 8] plumed(+0x146dd)[0x565489a2e6dd]
[runnervm76f27:12202] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0068c2a1ca]
[runnervm76f27:12202] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0068c2a28b]
[runnervm76f27:12202] [11] plumed(+0x15365)[0x565489a2f365]
[runnervm76f27:12202] *** End of error message ***
</pre>
{% endraw %}
