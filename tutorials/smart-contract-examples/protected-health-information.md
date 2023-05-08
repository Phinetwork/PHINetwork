# Protected Health Information



<pre class="language-solidity"><code class="lang-solidity">/// SPDX-License-Identifier: MIT
// Contract by PHI Network.

<strong>solidity
</strong>pragma solidity ^0.5.0;

contract HealthInformation {
  //The patient's required information
  struct Patient {
    address patientAddress;
    string patientName;
    string patientDOB;
    string patientGender;
    string patientMedicalData;
  }

  //Mapping of patient's info
  mapping(address => Patient) public patientData;

  //Function to add patient's info
  function addPatient(address _patientAddress, string memory _patientName, string memory _patientDOB, string memory _patientGender, string memory _patientMedicalData) public {
    patientData[_patientAddress].patientAddress = _patientAddress;
    patientData[_patientAddress].patientName = _patientName;
    patientData[_patientAddress].patientDOB = _patientDOB;
    patientData[_patientAddress].patientGender = _patientGender;
    patientData[_patientAddress].patientMedicalData = _patientMedicalData;
  }

  //Function to get patient's info
  function getPatient(address _patientAddress) public view returns (address, string memory, string memory, string memory, string memory) {
    return (patientData[_patientAddress].patientAddress, patientData[_patientAddress].patientName, patientData[_patientAddress].patientDOB, patientData[_patientAddress].patientGender, patientData[_patientAddress].patientMedicalData);
  }

  //Function to update patient's info
  function updatePatient(address _patientAddress, string memory _patientName, string memory _patientDOB, string memory _patientGender, string memory _patientMedicalData) public {
    patientData[_patientAddress].patientName = _patientName;
    patientData[_patientAddress].patientDOB = _patientDOB;
    patientData[_patientAddress].patientGender = _patientGender;
    patientData[_patientAddress].patientMedicalData = _patientMedicalData;
  }

  //Function to delete patient's info
  function deletePatient(address _patientAddress) public {
    delete patientData[_patientAddress];
  }
}

```
</code></pre>
