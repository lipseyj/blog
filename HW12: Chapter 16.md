<h3>16.9: Design the interfaces of components that might be used in a system for an emergency control room. You should design interfaces for a call-logging component that records calls made, and a vehicle discovery component that, gvien a post coe (zip code) and an incident type finds the nearest suitable vehicle to be dispatced to the incident.</h3>
<p>Call-Logging Component</p>
<table>
  <tr>
    <th>Requires Interface</th>
    <th>Component Name</th>
    <th>Provides Interface</th>
  </tr>
  <tr>
    <td>callData</td>
    <td></td>
    <td>recordCall</td>
  </tr>
  <tr>
    <td></td>
    <td>Call-Logging</td>
    <td>phoneNumber</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>dateTime</td>
  </tr>
</table>

<p>Vehicle-Discovery Component</p>
<table>
  <tr>
    <th>Requires Interface</th>
    <th>Component Name</th>
    <th>Provides Interface</th>
  </tr>
  <tr>
    <td>incidentType</td>
    <td></td>
    <td>findClosestVehicle</td>

  </tr>
  <tr>
    <td>zipcode</td>
    <td>Vehicle-Discovery</td>
    <td>suitableVehicle</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>sendVehicle</td>
  </tr>
</table>
