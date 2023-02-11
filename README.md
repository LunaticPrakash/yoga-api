# yoga-api
Might be the only information rich API for Yoga Poses.

## Status :-
In **Development**.

## Example of a single JSON Object from API :-
<img src="https://user-images.githubusercontent.com/56812557/218263082-a4dcda78-e571-4f99-b690-6896a7b4ae23.png" alt="Login Page" width="100%" height="100%" >

  <table>
    <thead>
      <th>Parameters</th>
      <th>Type</th>
      <th>Description</th>
  </thead>
  
  <tbody>
    <tr>
      <th>id</th>
      <td>Integer</td>
      <td>An unique identifier for each Yoga Pose.</td>
    </tr>
    
    <tr>
      <th>sanskrit_name</th>
      <td>String</td>
      <td>Name of the Yoga Pose in Sanskrit Language.</td>
    </tr>
    
    <tr>
      <th>english_name</th>
      <td>String</td>
      <td>Name of the Yoga Pose in English Language.</td>
    </tr>
    
    <tr>
      <th>procedure</th>
      <td>Array of Strings</td>
      <td>Procedure for doing the Yoga. Each element of array is the step that needs should be followed in sequential manner.</td>
    </tr>
    
    <tr>
      <th>targets</th>
      <td>Array of Strings</td>
      <td>The muscle group or body portions which will be targeted by that particular Yoga Pose.</td>
    </tr>
    
    <tr>
      <th>benefits</th>
      <td>Array of Strings</td>
      <td>List of benefits that will be achieved by practicing that particular Yoga Pose.</td>
    </tr>
    
    <tr>
      <th>contraindications</th>
      <td>Array of Strings</td>
      <td>List of the conditions when one should avoid doing that particular Yoga Pose.</td>
    </tr>
    
    <tr>
      <th>created_at</th>
      <td>String</td>
      <td>Actual time when that particular Yoga Pose was saved/created for first time in API.</td>
    </tr>
    
    <tr>
      <th>updated_at</th>
      <td>String</td>
      <td>Most recent time when any update has been done in that particular Yoga Pose.</td>
    </tr>
    
    <tr>
      <th>image_url</th>
      <td>String</td>
      <td>URL of the image of that particular Yoga Pose.</td>
    </tr>
    
    <tr>
      <th>yt_videos</th>
      <td>Array of URLs(String)</td>
      <td>List of URLs of the appropriate YouTube videos that explains about that particular Yoga Pose.</td>
    </tr>
    
  </tbody>
</table>


## Dev :- Prakash Gupta
