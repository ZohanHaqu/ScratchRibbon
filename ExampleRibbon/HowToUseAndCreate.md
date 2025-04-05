# How To Use ScratchRibbon

To use ScratchRibbon, you would have to do a few steps

# Step 1

first go to the solution explorer right click your project click on add, new item, or existing item and select an image or create an image so the ribbon is able to verify the image in here

# Step 2
Then go to MainWindow.xaml and add this code inside of it



```xml
<TabControl VerticalAlignment="Top" Height="100" Background="LightGray">
    <!-- Tab Home -->
    <TabItem Header="Home" Background="#FF0056FF" Foreground="#FFBCBCC3">
        <StackPanel Orientation="Horizontal" Margin="10,0">
            <!-- Ribbon Button with Image -->
            <Button Width="52" Height="50" BorderBrush="LightGray" Background="LightGray">
                <StackPanel>
                    <Image Source="example.png" Width="32" Height="32"/>
                    <TextBlock Text="Open" HorizontalAlignment="Center"/>
                </StackPanel>
            </Button>
            <Button Width="55" Height="50" BorderBrush="LightGray" Background="LightGray">
                <StackPanel>
                    <Image Source="example.png" Width="32" Height="32"/>
                    <TextBlock Text="Save" HorizontalAlignment="Center"/>
                </StackPanel>
            </Button>
        </StackPanel>
    </TabItem>
    
    <!-- Tab View -->
    <TabItem Header="View" Foreground="#FFBCBCC3">
        <TabItem.Background>
            <LinearGradientBrush EndPoint="0,1">
                <GradientStop Color="#FFF0F0F0"/>
                <GradientStop Color="#FF0056FF" Offset="1"/>
            </LinearGradientBrush>
        </TabItem.Background>
        <StackPanel Orientation="Horizontal" Margin="10,0">
            <!-- Ribbon Button with Image -->
            <Button Width="57" Height="50" Background="LightGray" BorderBrush="LightGray">
                <StackPanel>
                    <Image Source="example.png" Width="32" Height="32"/>
                    <TextBlock Text="Zoom In" HorizontalAlignment="Center"/>
                </StackPanel>
            </Button>
            <Button Width="60" Height="50" Background="LightGray" BorderBrush="LightGray">
                <StackPanel>
                    <Image Source="example.png" Width="32" Height="32"/>
                    <TextBlock Text="Zoom Out" HorizontalAlignment="Center"/>
                </StackPanel>
            </Button>
        </StackPanel>
    </TabItem>
</TabControl>"""

# Step 3

add your elements in mainwindow.xaml.cs to make the ribbon work and make sure you replace example.png to the image you imported

# Step 4

add your applications content on the app so home, and view will go to different types

# Step 5

Change your apps icons and settings

# Step 6

Changing the splash screen might be a good idea but its optional

# Step 7

if your happy with your app go to build and click Build <AppName> then its finished

# Step 8

open your app and test out the changes or click start if you want a quick run

# Step 9

Publish your app to the public or an private company

# Step 10

Everything is done and you can have stars, or many people might use your app.
