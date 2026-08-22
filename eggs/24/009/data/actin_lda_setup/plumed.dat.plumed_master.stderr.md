**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervm76f27:06774] *** Process received signal ***
[runnervm76f27:06774] Signal: Aborted (6)
[runnervm76f27:06774] Signal code:  (-6)
[runnervm76f27:06774] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8706a45330]
[runnervm76f27:06774] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8706a9ec0c]
[runnervm76f27:06774] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8706a4527e]
[runnervm76f27:06774] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8706a288ff]
[runnervm76f27:06774] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8706ea5ff5]
[runnervm76f27:06774] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8706ebb0da]
[runnervm76f27:06774] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8706ea5a55]
[runnervm76f27:06774] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8706ea5a6f]
[runnervm76f27:06774] [ 8] plumed_master(+0x146dd)[0x556ac11b26dd]
[runnervm76f27:06774] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8706a2a1ca]
[runnervm76f27:06774] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8706a2a28b]
[runnervm76f27:06774] [11] plumed_master(+0x15365)[0x556ac11b3365]
[runnervm76f27:06774] *** End of error message ***
</pre>
{% endraw %}
