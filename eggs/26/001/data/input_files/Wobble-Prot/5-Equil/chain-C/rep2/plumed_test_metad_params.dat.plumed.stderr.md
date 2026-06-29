**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmmklqx:04851] *** Process received signal ***
[runnervmmklqx:04851] Signal: Aborted (6)
[runnervmmklqx:04851] Signal code:  (-6)
[runnervmmklqx:04851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5386845330]
[runnervmmklqx:04851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f538689eb2c]
[runnervmmklqx:04851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f538684527e]
[runnervmmklqx:04851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53868288ff]
[runnervmmklqx:04851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5386ca5ff5]
[runnervmmklqx:04851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5386cbb0da]
[runnervmmklqx:04851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5386ca5a55]
[runnervmmklqx:04851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5386ca5a6f]
[runnervmmklqx:04851] [ 8] plumed(+0x146dd)[0x564a61a876dd]
[runnervmmklqx:04851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f538682a1ca]
[runnervmmklqx:04851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f538682a28b]
[runnervmmklqx:04851] [11] plumed(+0x15365)[0x564a61a88365]
[runnervmmklqx:04851] *** End of error message ***
</pre>
{% endraw %}
