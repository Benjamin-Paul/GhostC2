The tmp folder is used to store temporary custom payloads produced by the ``main_attacker`` object.

The payloads are stored as ``.py`` or ``.exe`` files with randomized alphanumeric names.

In patricular, those payloads are created by the ``winplant``, ``linplant`` and ``exeplant`` methods of the ``Attacker`` class (implemented in the ``attacker.py`` module located [here](/src/modules/attacker.py)). The temporary scripts are used at runtime to be dispatched on targets machines.


<h2>Cleaning</h2>

To erase all temporary files at once, run the powershell script [clean_tmp.ps1](/src/scripts/clean_tmp.ps1)