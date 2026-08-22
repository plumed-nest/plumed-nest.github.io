**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:06423] *** Process received signal ***
[runnervm76f27:06423] Signal: Aborted (6)
[runnervm76f27:06423] Signal code:  (-6)
[runnervm76f27:06423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d1ba45330]
[runnervm76f27:06423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d1ba9ec0c]
[runnervm76f27:06423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d1ba4527e]
[runnervm76f27:06423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d1ba288ff]
[runnervm76f27:06423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d1bea5ff5]
[runnervm76f27:06423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d1bebb0da]
[runnervm76f27:06423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d1bea5a55]
[runnervm76f27:06423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d1bea5a6f]
[runnervm76f27:06423] [ 8] plumed(+0x146dd)[0x562f2a3176dd]
[runnervm76f27:06423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d1ba2a1ca]
[runnervm76f27:06423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d1ba2a28b]
[runnervm76f27:06423] [11] plumed(+0x15365)[0x562f2a318365]
[runnervm76f27:06423] *** End of error message ***
</pre>
{% endraw %}
