**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmeorf1:05029] *** Process received signal ***
[runnervmeorf1:05029] Signal: Aborted (6)
[runnervmeorf1:05029] Signal code:  (-6)
[runnervmeorf1:05029] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23f4445330]
[runnervmeorf1:05029] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23f449eb2c]
[runnervmeorf1:05029] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23f444527e]
[runnervmeorf1:05029] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23f44288ff]
[runnervmeorf1:05029] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23f48a5ff5]
[runnervmeorf1:05029] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23f48bb0da]
[runnervmeorf1:05029] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23f48a5a55]
[runnervmeorf1:05029] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23f48a5a6f]
[runnervmeorf1:05029] [ 8] plumed(+0x146dd)[0x55d9529026dd]
[runnervmeorf1:05029] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23f442a1ca]
[runnervmeorf1:05029] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23f442a28b]
[runnervmeorf1:05029] [11] plumed(+0x15365)[0x55d952903365]
[runnervmeorf1:05029] *** End of error message ***
</pre>
{% endraw %}
