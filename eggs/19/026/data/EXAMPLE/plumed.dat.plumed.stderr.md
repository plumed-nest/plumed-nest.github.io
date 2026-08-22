**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervm76f27:11739] *** Process received signal ***
[runnervm76f27:11739] Signal: Aborted (6)
[runnervm76f27:11739] Signal code:  (-6)
[runnervm76f27:11739] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71d5845330]
[runnervm76f27:11739] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71d589ec0c]
[runnervm76f27:11739] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71d584527e]
[runnervm76f27:11739] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71d58288ff]
[runnervm76f27:11739] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71d5ca5ff5]
[runnervm76f27:11739] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71d5cbb0da]
[runnervm76f27:11739] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71d5ca5a55]
[runnervm76f27:11739] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71d5ca5a6f]
[runnervm76f27:11739] [ 8] plumed(+0x146dd)[0x55ea75f4e6dd]
[runnervm76f27:11739] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71d582a1ca]
[runnervm76f27:11739] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71d582a28b]
[runnervm76f27:11739] [11] plumed(+0x15365)[0x55ea75f4f365]
[runnervm76f27:11739] *** End of error message ***
</pre>
{% endraw %}
