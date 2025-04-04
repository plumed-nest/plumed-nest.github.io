**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1360-658:07227] *** Process received signal ***
[fv-az1360-658:07227] Signal: Aborted (6)
[fv-az1360-658:07227] Signal code:  (-6)
[fv-az1360-658:07227] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd8aa45330]
[fv-az1360-658:07227] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd8aa9eb2c]
[fv-az1360-658:07227] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd8aa4527e]
[fv-az1360-658:07227] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd8aa288ff]
[fv-az1360-658:07227] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd8aea5ff5]
[fv-az1360-658:07227] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd8aebb0da]
[fv-az1360-658:07227] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd8aea5a55]
[fv-az1360-658:07227] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd8aea5a6f]
[fv-az1360-658:07227] [ 8] plumed(+0x146dd)[0x55794afd36dd]
[fv-az1360-658:07227] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd8aa2a1ca]
[fv-az1360-658:07227] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd8aa2a28b]
[fv-az1360-658:07227] [11] plumed(+0x15365)[0x55794afd4365]
[fv-az1360-658:07227] *** End of error message ***
</pre>
{% endraw %}
