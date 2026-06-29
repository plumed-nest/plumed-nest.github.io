**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmmklqx:09399] *** Process received signal ***
[runnervmmklqx:09399] Signal: Aborted (6)
[runnervmmklqx:09399] Signal code:  (-6)
[runnervmmklqx:09399] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a89645330]
[runnervmmklqx:09399] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a8969eb2c]
[runnervmmklqx:09399] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a8964527e]
[runnervmmklqx:09399] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a896288ff]
[runnervmmklqx:09399] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a89aa5ff5]
[runnervmmklqx:09399] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a89abb0da]
[runnervmmklqx:09399] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a89aa5a55]
[runnervmmklqx:09399] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a89aa5a6f]
[runnervmmklqx:09399] [ 8] plumed_master(+0x146dd)[0x5556fd8166dd]
[runnervmmklqx:09399] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a8962a1ca]
[runnervmmklqx:09399] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a8962a28b]
[runnervmmklqx:09399] [11] plumed_master(+0x15365)[0x5556fd817365]
[runnervmmklqx:09399] *** End of error message ***
</pre>
{% endraw %}
