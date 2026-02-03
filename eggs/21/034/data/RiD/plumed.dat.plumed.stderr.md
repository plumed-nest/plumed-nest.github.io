**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmkj6or:07602] *** Process received signal ***
[runnervmkj6or:07602] Signal: Aborted (6)
[runnervmkj6or:07602] Signal code:  (-6)
[runnervmkj6or:07602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1312645330]
[runnervmkj6or:07602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f131269eb2c]
[runnervmkj6or:07602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f131264527e]
[runnervmkj6or:07602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13126288ff]
[runnervmkj6or:07602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1312aa5ff5]
[runnervmkj6or:07602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1312abb0da]
[runnervmkj6or:07602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1312aa5a55]
[runnervmkj6or:07602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1312aa5a6f]
[runnervmkj6or:07602] [ 8] plumed(+0x146dd)[0x561b255416dd]
[runnervmkj6or:07602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f131262a1ca]
[runnervmkj6or:07602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f131262a28b]
[runnervmkj6or:07602] [11] plumed(+0x15365)[0x561b25542365]
[runnervmkj6or:07602] *** End of error message ***
</pre>
{% endraw %}
