<!DOCTYPE html>
<html>
<head>
<script src="http://maps.googleapis.com/maps/api/js?key=AIzaSyAZi4epp-NctvuWW-dyvGUlhlX-_GZrXlE&sensor=false">
</script>
 
 <script>
 var geocoder = new google.maps.Geocoder();
 var map;
 function initialize()
 {
  
  var mapProp = {
    center:new google.maps.LatLng(38,-97),
      zoom:6,
        mapTypeId:google.maps.MapTypeId.TERRAIN
          };
          map=new google.maps.Map(document.getElementById("googleMap")
            ,mapProp);
             
              mapzip("22657");
              mapzip("22801");
              mapzip("23454");
              mapzip("60005");
              mapzip("24401");
              mapzip("22901");
              mapzip("06877");
              mapzip("22812");
              mapzip("22824");
              mapzip("20171");
              mapzip("20723");
              mapzip("22801");
              mapzip("20902");
              mapzip("08085");
              mapzip("22932");
              mapzip("22213");
              mapzip("22827");
              mapzip("23602");
              mapzip("21012");
              mapzip("23456");
              mapzip("20152");
              mapzip("23221");
              mapzip("20878");
              mapzip("22192");
              mapzip("24153");
              mapzip("23228");
              mapzip("10598");
              mapzip("22207");
              mapzip("23322");
              mapzip("08048");
              mapzip("20147");
              mapzip("22844");
              mapzip("22192");
              mapzip("22508");
              mapzip("22835");
              mapzip("23322");
              mapzip("22407");
              mapzip("23451");
              mapzip("22801");
              mapzip("23226");
              mapzip("22485");
              mapzip("23454");
              mapzip("23452");
              mapzip("14424");
              mapzip("22015");
              mapzip("24502");
              mapzip("20120");
              mapzip("22551");
              mapzip("23456");
              mapzip("20877");
              mapzip("20148");
              mapzip("21061");
              mapzip("20164");
              mapzip("17325");
              mapzip("22815");
              mapzip("22030");
              mapzip("20132");
              mapzip("22520");
              mapzip("22802");
              mapzip("23834");
              mapzip("24541");
              mapzip("23024");
              mapzip("23124");
              mapzip("23005");
              mapzip("24354");
              mapzip("22534");
              mapzip("22630");
              mapzip("22603");
              mapzip("22554");
              mapzip("23005");
              mapzip("22801");
              mapzip("07921");
              mapzip("21042");
              mapzip("21012");
              mapzip("07739");
              mapzip("22205");
              mapzip("20194");
              mapzip("22066");
              mapzip("23226");
              mapzip("22701");
              mapzip("20176");
              mapzip("22153");
              mapzip("22003");
              mapzip("22801");
              mapzip("24019");
              mapzip("28560");
              mapzip("22801");
              mapzip("22102");
              mapzip("20147");
              mapzip("20158");
              mapzip("22408");
              mapzip("20119");
              mapzip("23664");
              mapzip("20151");
              mapzip("22193");
              mapzip("21043");
              mapzip("22153");
              mapzip("23693");
              mapzip("22630");
              mapzip("11792");
              mapzip("24018");
              mapzip("20171");
              mapzip("22205");
              mapzip("20112");
              mapzip("20137");
              mapzip("23455");
              mapzip("10475");
              mapzip("22181");
              mapzip("22737");
              mapzip("19465");
              mapzip("22801");
              mapzip("23322");
              mapzip("21784");
              mapzip("24060");
              mapzip("23455");
              mapzip("22152");
              mapzip("23693");
              mapzip("23185");
              mapzip("22482");
              mapzip("00434");
              mapzip("24426");
              mapzip("22801");
              mapzip("22192");
              mapzip("23059");
              mapzip("30542");
              mapzip("22207");
              mapzip("23301");
              mapzip("23456");
              mapzip("24112");
              mapzip("7843");
              mapzip("21784");
              mapzip("20878");
              mapzip("23185");
              mapzip("19335");
              mapzip("08801");
              mapzip("20121");
              mapzip("22041");
              mapzip("23451");
              mapzip("22030");
              mapzip("22936");
              mapzip("22936");
              
              }
               
               function mapzip(zip){
               geocoder.geocode( { 'address': zip}, function(results, status) {
               if (status == google.maps.GeocoderStatus.OK) {
                map.setCenter(results[0].geometry.location);
                var marker = new google.maps.Marker({
                  map: map,
                    position: results[0].geometry.location
                               });
                                    } else {
                                         alert('Geocode was not successful for the following reason: ' + status);
                                                   }
                                                           });
                                                            
                                                              
                                                               
                                                               }
                                                                
                                                                 
                                                                  
                                                                   
                                                                    
                                                                    google.maps.event.addDomListener(window, 'load', initialize);
                                                                    </script>
                                                                     
                                                                     </head>
                                                                      
                                                                      <body>
                                                                      <center><div id="googleMap" style="width:1000px;height:760px;"></div></center>
                                                                       
                                                                       </body>
                                                                       </html>
                                                                                                                                        
                                                                                                                                         
                                                                                                                                         }
                                                                                                                                          
                                                                                                                                           
                                                                                                                                            
                                                                                                                                             
                                                                                                                                              
                                                                                                                                              google.maps.event.addDomListener(window, 'load', initialize);
                                                                                                                                              </script>
                                                                                                                                               
                                                                                                                                               </head>
                                                                                                                                                
                                                                                                                                                <body>
                                                                                                                                                <center><div id="googleMap" style="width:1000px;height:760px;"></div></center>
                                                                                                                                                 
                                                                                                                                                 </body>
                                                                                                                                                 </html>
