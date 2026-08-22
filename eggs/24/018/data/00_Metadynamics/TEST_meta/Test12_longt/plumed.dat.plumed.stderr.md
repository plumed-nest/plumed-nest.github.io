**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:05858] *** Process received signal ***
[runnervm76f27:05858] Signal: Aborted (6)
[runnervm76f27:05858] Signal code:  (-6)
[runnervm76f27:05858] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f82b0a45330]
[runnervm76f27:05858] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f82b0a9ec0c]
[runnervm76f27:05858] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f82b0a4527e]
[runnervm76f27:05858] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82b0a288ff]
[runnervm76f27:05858] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82b0ea5ff5]
[runnervm76f27:05858] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82b0ebb0da]
[runnervm76f27:05858] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82b0ea5a55]
[runnervm76f27:05858] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82b0ea5a6f]
[runnervm76f27:05858] [ 8] plumed(+0x146dd)[0x562e2f5e96dd]
[runnervm76f27:05858] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f82b0a2a1ca]
[runnervm76f27:05858] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f82b0a2a28b]
[runnervm76f27:05858] [11] plumed(+0x15365)[0x562e2f5ea365]
[runnervm76f27:05858] *** End of error message ***
</pre>
{% endraw %}
