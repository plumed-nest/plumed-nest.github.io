**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmeorf1:07389] *** Process received signal ***
[runnervmeorf1:07389] Signal: Aborted (6)
[runnervmeorf1:07389] Signal code:  (-6)
[runnervmeorf1:07389] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0797445330]
[runnervmeorf1:07389] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f079749eb2c]
[runnervmeorf1:07389] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f079744527e]
[runnervmeorf1:07389] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07974288ff]
[runnervmeorf1:07389] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07978a5ff5]
[runnervmeorf1:07389] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07978bb0da]
[runnervmeorf1:07389] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07978a5a55]
[runnervmeorf1:07389] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07978a5a6f]
[runnervmeorf1:07389] [ 8] plumed_master(+0x146dd)[0x5562df8fb6dd]
[runnervmeorf1:07389] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f079742a1ca]
[runnervmeorf1:07389] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f079742a28b]
[runnervmeorf1:07389] [11] plumed_master(+0x15365)[0x5562df8fc365]
[runnervmeorf1:07389] *** End of error message ***
</pre>
{% endraw %}
