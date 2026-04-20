**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmeorf1:05045] *** Process received signal ***
[runnervmeorf1:05045] Signal: Aborted (6)
[runnervmeorf1:05045] Signal code:  (-6)
[runnervmeorf1:05045] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4fa8245330]
[runnervmeorf1:05045] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4fa829eb2c]
[runnervmeorf1:05045] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4fa824527e]
[runnervmeorf1:05045] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4fa82288ff]
[runnervmeorf1:05045] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4fa86a5ff5]
[runnervmeorf1:05045] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4fa86bb0da]
[runnervmeorf1:05045] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4fa86a5a55]
[runnervmeorf1:05045] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4fa86a5a6f]
[runnervmeorf1:05045] [ 8] plumed_master(+0x146dd)[0x5640c17ac6dd]
[runnervmeorf1:05045] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4fa822a1ca]
[runnervmeorf1:05045] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4fa822a28b]
[runnervmeorf1:05045] [11] plumed_master(+0x15365)[0x5640c17ad365]
[runnervmeorf1:05045] *** End of error message ***
</pre>
{% endraw %}
