# thestart
<Panel ux:Class="Raindrop">
    <Image Width="15" Height="15" File="Assets/raindrops.png" Color="{dropletcolor}">
        <Rotation Degrees="20.6" />
    </Image>
</Panel>

<Grid ux:Class="RaindropRow" ColumnCount="3">
    <Raindrop ux:Name="drop1"/>
    <Raindrop ux:Name="drop2"/>
    <Raindrop ux:Name="drop3"/>
</Grid>
