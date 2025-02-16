**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1440-40:60878] *** Process received signal ***
[fv-az1440-40:60878] Signal: Aborted (6)
[fv-az1440-40:60878] Signal code:  (-6)
[fv-az1440-40:60878] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab3aa45330]
[fv-az1440-40:60878] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab3aa9eb2c]
[fv-az1440-40:60878] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab3aa4527e]
[fv-az1440-40:60878] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab3aa288ff]
[fv-az1440-40:60878] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab3aea5ff5]
[fv-az1440-40:60878] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab3aebb0da]
[fv-az1440-40:60878] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab3aea5a55]
[fv-az1440-40:60878] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab3aea5a6f]
[fv-az1440-40:60878] [ 8] plumed_master(+0x146dd)[0x563df7db56dd]
[fv-az1440-40:60878] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab3aa2a1ca]
[fv-az1440-40:60878] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab3aa2a28b]
[fv-az1440-40:60878] [11] plumed_master(+0x15365)[0x563df7db6365]
[fv-az1440-40:60878] *** End of error message ***
</pre>
{% endraw %}
