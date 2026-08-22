**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervm76f27:06758] *** Process received signal ***
[runnervm76f27:06758] Signal: Aborted (6)
[runnervm76f27:06758] Signal code:  (-6)
[runnervm76f27:06758] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0106a45330]
[runnervm76f27:06758] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0106a9ec0c]
[runnervm76f27:06758] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0106a4527e]
[runnervm76f27:06758] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0106a288ff]
[runnervm76f27:06758] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0106ea5ff5]
[runnervm76f27:06758] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0106ebb0da]
[runnervm76f27:06758] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0106ea5a55]
[runnervm76f27:06758] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0106ea5a6f]
[runnervm76f27:06758] [ 8] plumed(+0x146dd)[0x564cf3d0c6dd]
[runnervm76f27:06758] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0106a2a1ca]
[runnervm76f27:06758] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0106a2a28b]
[runnervm76f27:06758] [11] plumed(+0x15365)[0x564cf3d0d365]
[runnervm76f27:06758] *** End of error message ***
</pre>
{% endraw %}
