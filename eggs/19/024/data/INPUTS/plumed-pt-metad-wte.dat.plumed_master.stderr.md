**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[pkrvmbietmlfzoi:66265] *** Process received signal ***
[pkrvmbietmlfzoi:66265] Signal: Aborted (6)
[pkrvmbietmlfzoi:66265] Signal code:  (-6)
[pkrvmbietmlfzoi:66265] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b49045330]
[pkrvmbietmlfzoi:66265] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b4909eb2c]
[pkrvmbietmlfzoi:66265] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b4904527e]
[pkrvmbietmlfzoi:66265] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b490288ff]
[pkrvmbietmlfzoi:66265] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b494a5ff5]
[pkrvmbietmlfzoi:66265] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b494bb0da]
[pkrvmbietmlfzoi:66265] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b494a5a55]
[pkrvmbietmlfzoi:66265] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b494a5a6f]
[pkrvmbietmlfzoi:66265] [ 8] plumed_master(+0x146dd)[0x56295f9846dd]
[pkrvmbietmlfzoi:66265] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b4902a1ca]
[pkrvmbietmlfzoi:66265] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b4902a28b]
[pkrvmbietmlfzoi:66265] [11] plumed_master(+0x15365)[0x56295f985365]
[pkrvmbietmlfzoi:66265] *** End of error message ***
</pre>
{% endraw %}
