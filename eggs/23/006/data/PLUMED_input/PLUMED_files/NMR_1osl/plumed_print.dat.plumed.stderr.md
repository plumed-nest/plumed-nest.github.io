**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[runnervmvrwv9:06815] *** Process received signal ***
[runnervmvrwv9:06815] Signal: Aborted (6)
[runnervmvrwv9:06815] Signal code:  (-6)
[runnervmvrwv9:06815] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb30fe45330]
[runnervmvrwv9:06815] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb30fe9eb2c]
[runnervmvrwv9:06815] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb30fe4527e]
[runnervmvrwv9:06815] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb30fe288ff]
[runnervmvrwv9:06815] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3102a5ff5]
[runnervmvrwv9:06815] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3102bb0da]
[runnervmvrwv9:06815] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3102a5a55]
[runnervmvrwv9:06815] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3102a5a6f]
[runnervmvrwv9:06815] [ 8] plumed(+0x146dd)[0x5578b695f6dd]
[runnervmvrwv9:06815] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb30fe2a1ca]
[runnervmvrwv9:06815] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb30fe2a28b]
[runnervmvrwv9:06815] [11] plumed(+0x15365)[0x5578b6960365]
[runnervmvrwv9:06815] *** End of error message ***
</pre>
{% endraw %}
