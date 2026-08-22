**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervm76f27:04722] *** Process received signal ***
[runnervm76f27:04722] Signal: Aborted (6)
[runnervm76f27:04722] Signal code:  (-6)
[runnervm76f27:04722] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f54ae445330]
[runnervm76f27:04722] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f54ae49ec0c]
[runnervm76f27:04722] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f54ae44527e]
[runnervm76f27:04722] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f54ae4288ff]
[runnervm76f27:04722] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f54ae8a5ff5]
[runnervm76f27:04722] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f54ae8bb0da]
[runnervm76f27:04722] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f54ae8a5a55]
[runnervm76f27:04722] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f54ae8a5a6f]
[runnervm76f27:04722] [ 8] plumed(+0x146dd)[0x558cb5e776dd]
[runnervm76f27:04722] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f54ae42a1ca]
[runnervm76f27:04722] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f54ae42a28b]
[runnervm76f27:04722] [11] plumed(+0x15365)[0x558cb5e78365]
[runnervm76f27:04722] *** End of error message ***
</pre>
{% endraw %}
