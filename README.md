`displayInfo("IP Address", ipData.YourFuckingIPAddress);`
Gets the IP address of target

`displayInfo("Country", locationData.country);`
Gets Country from target

`displayInfo("Full Location", ipData.YourFuckingLocation);`
Wraps every country, zip, region and city into a full location of the target

`await displayInfo("Latitude", locationData.lat);
        await displayInfo("Longitude", locationData.lon);`
Displays targets coords

`displayInfo("ISP", locationData.isp);`
Displays targets ISP provider

`await displayInfo("Autonomous System", locationData.as);
        await displayInfo("Browser Name", browserData.name);
        await displayInfo("Platform Name", browserData.platform);
        await displayInfo("Browser Version", browserData.version);
        await displayInfo("Mobile/Tablet", browserData.isMobile || browserData.isTablet ? "Yes" : 'No');
        await displayInfo("Referrer", document.referrer || "None");
        await displayInfo("System Languages", navigator.languages.join(", "));
        await displayInfo("Screen Width", screen.width, 'px');
        await displayInfo("Screen Height", screen.height, 'px');` 

        
Displays a fuck ton of specs from the target to identify what device he visited your domain from.
        
