**Project ID:** [plumID:24.026]({{ '/' | absolute_url }}eggs/24/026/)  
Stderr for source:  CpHMD_metaD/scripts/PLUMED_GRID.dat   
Download: [zipped raw stdout](PLUMED_GRID.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](PLUMED_GRID.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[runnervmvrwv9:05334] *** Process received signal ***
[runnervmvrwv9:05334] Signal: Aborted (6)
[runnervmvrwv9:05334] Signal code:  (-6)
[runnervmvrwv9:05334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb54445330]
[runnervmvrwv9:05334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb5449eb2c]
[runnervmvrwv9:05334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb5444527e]
[runnervmvrwv9:05334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb544288ff]
[runnervmvrwv9:05334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb548a5ff5]
[runnervmvrwv9:05334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb548bb0da]
[runnervmvrwv9:05334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb548a5a55]
[runnervmvrwv9:05334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb548a5a6f]
[runnervmvrwv9:05334] [ 8] plumed_master(+0x146dd)[0x55846592a6dd]
[runnervmvrwv9:05334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb5442a1ca]
[runnervmvrwv9:05334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb5442a28b]
[runnervmvrwv9:05334] [11] plumed_master(+0x15365)[0x55846592b365]
[runnervmvrwv9:05334] *** End of error message ***
</pre>
{% endraw %}
