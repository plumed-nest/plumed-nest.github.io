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
[fv-az797-511:07591] *** Process received signal ***
[fv-az797-511:07591] Signal: Aborted (6)
[fv-az797-511:07591] Signal code:  (-6)
[fv-az797-511:07591] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2789045330]
[fv-az797-511:07591] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f278909eb2c]
[fv-az797-511:07591] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f278904527e]
[fv-az797-511:07591] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f27890288ff]
[fv-az797-511:07591] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f27894a5ff5]
[fv-az797-511:07591] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f27894bb0da]
[fv-az797-511:07591] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f27894a5a55]
[fv-az797-511:07591] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f27894a5a6f]
[fv-az797-511:07591] [ 8] plumed(+0x146dd)[0x56282f0a76dd]
[fv-az797-511:07591] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f278902a1ca]
[fv-az797-511:07591] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f278902a28b]
[fv-az797-511:07591] [11] plumed(+0x15365)[0x56282f0a8365]
[fv-az797-511:07591] *** End of error message ***
</pre>
{% endraw %}
