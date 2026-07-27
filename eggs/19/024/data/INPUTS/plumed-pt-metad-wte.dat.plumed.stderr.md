**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[runnervmvrwv9:07565] *** Process received signal ***
[runnervmvrwv9:07565] Signal: Aborted (6)
[runnervmvrwv9:07565] Signal code:  (-6)
[runnervmvrwv9:07565] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fadd8445330]
[runnervmvrwv9:07565] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fadd849eb2c]
[runnervmvrwv9:07565] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fadd844527e]
[runnervmvrwv9:07565] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fadd84288ff]
[runnervmvrwv9:07565] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fadd88a5ff5]
[runnervmvrwv9:07565] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fadd88bb0da]
[runnervmvrwv9:07565] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fadd88a5a55]
[runnervmvrwv9:07565] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fadd88a5a6f]
[runnervmvrwv9:07565] [ 8] plumed(+0x146dd)[0x5556e62f86dd]
[runnervmvrwv9:07565] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fadd842a1ca]
[runnervmvrwv9:07565] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fadd842a28b]
[runnervmvrwv9:07565] [11] plumed(+0x15365)[0x5556e62f9365]
[runnervmvrwv9:07565] *** End of error message ***
</pre>
{% endraw %}
