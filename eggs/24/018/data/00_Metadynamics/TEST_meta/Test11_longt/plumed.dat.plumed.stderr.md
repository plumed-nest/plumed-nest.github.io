**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:05806] *** Process received signal ***
[runnervm76f27:05806] Signal: Aborted (6)
[runnervm76f27:05806] Signal code:  (-6)
[runnervm76f27:05806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f09ef845330]
[runnervm76f27:05806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f09ef89ec0c]
[runnervm76f27:05806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f09ef84527e]
[runnervm76f27:05806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09ef8288ff]
[runnervm76f27:05806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09efca5ff5]
[runnervm76f27:05806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09efcbb0da]
[runnervm76f27:05806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09efca5a55]
[runnervm76f27:05806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09efca5a6f]
[runnervm76f27:05806] [ 8] plumed(+0x146dd)[0x55598e9076dd]
[runnervm76f27:05806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f09ef82a1ca]
[runnervm76f27:05806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f09ef82a28b]
[runnervm76f27:05806] [11] plumed(+0x15365)[0x55598e908365]
[runnervm76f27:05806] *** End of error message ***
</pre>
{% endraw %}
