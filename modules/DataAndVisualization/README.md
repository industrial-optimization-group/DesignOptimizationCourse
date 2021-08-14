# List of each file and its explanation
No guarantee that the details are correct... Should be.
## Geometry design problem, variable count = 12:

| file name     | Details             |
| ------------- | -------------       |
| gd1           | No constraints      |
| gd2           | volume > 0.2, min height > 0.5 and floor area > 0.5|
| gd3           | Ignore floor area. No constraints|

## Geometry design problems with constant floor, variable count = 12:

| file name     | Details             |
| ------------- | -------------       |
| gdf1          | No constraints      |
| gdf2          | min height > 0.3    |
| gdf3          | min height > 0.75 and volume < 0.5. Trying to achieve some pyramid shaped buildings|  
| gdf4          | min height < 0.6    |  
| gdf4          | surface area > 3 and volume > 0.5    |  



## Two bar truss problem, load = 65
| file name     | Details             |
| ------------- | -------------       |
| tb1           | Optimize everything, No constraints      |
| tb2           | Only weight and stress. No constraints. Has non optimal solutions...     |
| tb3           | Optimize everything, 10 < weight < 100, stress > 15 and buckling stress < 100  |
| tb3           | Optimize everything but deflection, 25 < weight < 75, 15 < stress < 50, 10 < buckling <50, deflection  < 2  |
