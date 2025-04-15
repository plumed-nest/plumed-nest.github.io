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
[fv-az1693-957:62228] *** Process received signal ***
[fv-az1693-957:62228] Signal: Aborted (6)
[fv-az1693-957:62228] Signal code:  (-6)
[fv-az1693-957:62228] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f172e045330]
[fv-az1693-957:62228] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f172e09eb2c]
[fv-az1693-957:62228] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f172e04527e]
[fv-az1693-957:62228] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f172e0288ff]
[fv-az1693-957:62228] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f172e4a5ff5]
[fv-az1693-957:62228] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f172e4bb0da]
[fv-az1693-957:62228] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f172e4a5a55]
[fv-az1693-957:62228] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f172e4a5a6f]
[fv-az1693-957:62228] [ 8] plumed(+0x146dd)[0x555c68cfa6dd]
[fv-az1693-957:62228] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f172e02a1ca]
[fv-az1693-957:62228] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f172e02a28b]
[fv-az1693-957:62228] [11] plumed(+0x15365)[0x555c68cfb365]
[fv-az1693-957:62228] *** End of error message ***
</pre>
{% endraw %}
