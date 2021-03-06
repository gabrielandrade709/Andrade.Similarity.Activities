# UiPath Activity: Similarity between terms in a Data Table

## Summary
1. [Package in UiPath](#PackageInUiPath)
2. [Required parameters to be filled](#RequiredParametersToBeFilled)
3. [Optional parameters](#OptionalParameters)

---

Activity from UiPath that can be able to look for similarity between terms in a Data Table.


## Package in UiPath <a name="PackageInUiPath"></a>

![image](https://user-images.githubusercontent.com/17112000/169679939-8b7784d4-0b33-4650-812f-16c63b0026d8.png)


## Required parameters to be filled <a name="RequiredParametersToBeFilled"></a>

You'll need to fill the following fields:

**Term to be found**: term that you'd like to be found;

**DataTable**: data table that where will be search the term;

**Similarity to be found**: similarity that you want to be found;

**Look for the biggest similarity**: set this parameter to "True" if you want to look for the biggest similarity term in the entire Data Table. Set this parameter to "False" if you just want to get the term that hit the similarity defined;

**Column name**: column name where will be search the term.

**Example**:

![image](https://user-images.githubusercontent.com/17112000/168869284-0d3bf020-626b-4e23-900d-675856c85f5e.png)


## Optional parameters <a name="OptionalParameters"></a>

**Found similarity**: similarity that was found;

**Found term**: term that was found.

**Example**:

![image](https://user-images.githubusercontent.com/17112000/168869988-c0edae44-4dae-4d80-8e28-f34a8b6a7dea.png)


Once the parameters are filled in correctly, you can perform the activity and it will work!
