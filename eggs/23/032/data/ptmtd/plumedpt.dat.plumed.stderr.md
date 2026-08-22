**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervm76f27:04773] *** Process received signal ***
[runnervm76f27:04773] Signal: Aborted (6)
[runnervm76f27:04773] Signal code:  (-6)
[runnervm76f27:04773] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e4aa45330]
[runnervm76f27:04773] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e4aa9ec0c]
[runnervm76f27:04773] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e4aa4527e]
[runnervm76f27:04773] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e4aa288ff]
[runnervm76f27:04773] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e4aea5ff5]
[runnervm76f27:04773] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e4aebb0da]
[runnervm76f27:04773] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e4aea5a55]
[runnervm76f27:04773] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e4aea5a6f]
[runnervm76f27:04773] [ 8] plumed(+0x146dd)[0x55a6e08ea6dd]
[runnervm76f27:04773] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e4aa2a1ca]
[runnervm76f27:04773] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e4aa2a28b]
[runnervm76f27:04773] [11] plumed(+0x15365)[0x55a6e08eb365]
[runnervm76f27:04773] *** End of error message ***
</pre>
{% endraw %}
