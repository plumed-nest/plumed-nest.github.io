**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:06439] *** Process received signal ***
[runnervm76f27:06439] Signal: Aborted (6)
[runnervm76f27:06439] Signal code:  (-6)
[runnervm76f27:06439] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1cbe445330]
[runnervm76f27:06439] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1cbe49ec0c]
[runnervm76f27:06439] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1cbe44527e]
[runnervm76f27:06439] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1cbe4288ff]
[runnervm76f27:06439] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1cbe8a5ff5]
[runnervm76f27:06439] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1cbe8bb0da]
[runnervm76f27:06439] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1cbe8a5a55]
[runnervm76f27:06439] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1cbe8a5a6f]
[runnervm76f27:06439] [ 8] plumed_master(+0x146dd)[0x55ab61b0b6dd]
[runnervm76f27:06439] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1cbe42a1ca]
[runnervm76f27:06439] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1cbe42a28b]
[runnervm76f27:06439] [11] plumed_master(+0x15365)[0x55ab61b0c365]
[runnervm76f27:06439] *** End of error message ***
</pre>
{% endraw %}
