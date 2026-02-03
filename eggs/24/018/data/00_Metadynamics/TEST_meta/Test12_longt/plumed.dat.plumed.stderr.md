**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmkj6or:07021] *** Process received signal ***
[runnervmkj6or:07021] Signal: Aborted (6)
[runnervmkj6or:07021] Signal code:  (-6)
[runnervmkj6or:07021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f051d045330]
[runnervmkj6or:07021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f051d09eb2c]
[runnervmkj6or:07021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f051d04527e]
[runnervmkj6or:07021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f051d0288ff]
[runnervmkj6or:07021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f051d4a5ff5]
[runnervmkj6or:07021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f051d4bb0da]
[runnervmkj6or:07021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f051d4a5a55]
[runnervmkj6or:07021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f051d4a5a6f]
[runnervmkj6or:07021] [ 8] plumed(+0x146dd)[0x560cb3c6a6dd]
[runnervmkj6or:07021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f051d02a1ca]
[runnervmkj6or:07021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f051d02a28b]
[runnervmkj6or:07021] [11] plumed(+0x15365)[0x560cb3c6b365]
[runnervmkj6or:07021] *** End of error message ***
</pre>
{% endraw %}
