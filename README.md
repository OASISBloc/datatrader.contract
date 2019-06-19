# osbio.contracts

To build the contracts and the unit tests:
* First, ensure that your __OASISBloc__ is compiled to the core symbol for the OSBIO blockchain that intend to deploy to.
* Second, make sure that you have ```sudo make install```ed __OASISBloc__.
* Then just run the ```build.sh``` in the top directory to build all the contracts and the unit tests for these contracts.

After build:
* The unit tests executable is placed in the _build/tests_ and is named __unit_test__.
* The contracts are built into a _bin/\<contract name\>_ folder in their respective directories.
* Finally, simply use __closb__ to _set contract_ by pointing to the previously mentioned directory.

## License

[MIT](./LICENSE)

## Important

See LICENSE for copyright and license terms.  Foundation OASIS LTD. makes its contribution on a voluntary basis as a member of the OASISBloc community and is not responsible for ensuring the overall performance of the software or any related applications.  We make no representation, warranty, guarantee or undertaking in respect of the software or any related documentation, whether expressed or implied, including but not limited to the warranties or merchantability, fitness for a particular purpose and noninfringement. In no event shall we be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or documentation or the use or other dealings in the software or documentation.  Any test results or performance figures are indicative and will not reflect performance under all conditions.  Any reference to any third party or third-party product, service or other resource is not an endorsement or recommendation by Block.one.  We are not responsible, and disclaim any and all responsibility and liability, for your use of or reliance on any of these resources. Third-party resources may be updated, changed or terminated at any time, so the information here may be out of date or inaccurate.
