**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmkj6or:07665] *** Process received signal ***
[runnervmkj6or:07665] Signal: Aborted (6)
[runnervmkj6or:07665] Signal code:  (-6)
[runnervmkj6or:07665] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a35645330]
[runnervmkj6or:07665] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a3569eb2c]
[runnervmkj6or:07665] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a3564527e]
[runnervmkj6or:07665] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a356288ff]
[runnervmkj6or:07665] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a35aa5ff5]
[runnervmkj6or:07665] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a35abb0da]
[runnervmkj6or:07665] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a35aa5a55]
[runnervmkj6or:07665] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a35aa5a6f]
[runnervmkj6or:07665] [ 8] plumed(+0x146dd)[0x55fbf05796dd]
[runnervmkj6or:07665] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a3562a1ca]
[runnervmkj6or:07665] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a3562a28b]
[runnervmkj6or:07665] [11] plumed(+0x15365)[0x55fbf057a365]
[runnervmkj6or:07665] *** End of error message ***
</pre>
{% endraw %}
