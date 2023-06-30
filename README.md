# Rattleback, Tensor of inertia and plotting
The app is designed for plotting rattleback, calculating its tensor of inertia with and after changes, and calculating the angle.
By plotting a "rattleback" you are basically plotting an ellipsoid with z<=0, as a result you get a semi-ellipsoid.
The app will require you to enter the semi-axis of the ellipsoid.
Tensor of inertia is calculated by its defenition, the detailed process could be found here: https://math.stackexchange.com/questions/2792009/inertia-tensor-of-an-ellipsoid
Tensor of intertia of a half-ellipsoid is half of the inital ellipsoid because of integral properties.


# Tensor of inertia after changes
To the initial rattleback two rigid bodies of masses M are attached. Their positios are defined by lenght from the centre of full ellipsoid and angle of deviation from the inital axes.
This addition represents the mass displacement that transforms the semi-ellipsoid to a rattleback, acquiring it's properties.
The program calculates the tensor of inertia of this rattleback.
Afterwards, the program will calculate the angle by which the axes could be rotated in order for tensor of inertia to became diagonal for further calculation of the ellipsoid of energy.
