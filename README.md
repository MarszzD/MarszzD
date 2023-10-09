local G2L = {};

-- StarterGui.MainScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["Name"] = [[MainScreenGui]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;

-- StarterGui.MainScreenGui.Frame
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(61, 68, 75);
G2L["2"]["BackgroundTransparency"] = 0.699999988079071;
G2L["2"]["Size"] = UDim2.new(0.5442913770675659, 0, 0.48064514994621277, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Position"] = UDim2.new(0.24115154147148132, 0, 0.2709677517414093, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(28, 27, 28);
G2L["3"]["Size"] = UDim2.new(1.0021096467971802, 0, 0.9295302033424377, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Position"] = UDim2.new(-0.001154517289251089, 0, 0.13609017431735992, 0);
G2L["3"]["Name"] = [[MainFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.UIAspectRatioConstraint
G2L["4"] = Instance.new("UIAspectRatioConstraint", G2L["3"]);
G2L["4"]["AspectRatio"] = 1.7148014307022095;

-- StarterGui.MainScreenGui.Frame.MainFrame.UIStroke
G2L["5"] = Instance.new("UIStroke", G2L["3"]);
G2L["5"]["Transparency"] = 0.7200000286102295;

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat
G2L["6"] = Instance.new("TextButton", G2L["3"]);
G2L["6"]["TextWrapped"] = true;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["RichText"] = true;
G2L["6"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["TextScaled"] = true;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["TextSize"] = 14;
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6"]["TextColor3"] = Color3.fromRGB(62, 60, 62);
G2L["6"]["Size"] = UDim2.new(0.38736841082572937, 0, 0.08303248882293701, 0);
G2L["6"]["Name"] = [[Combat]];
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[Combat]];
G2L["6"]["Position"] = UDim2.new(0.04636840894818306, 0, 0.08638986200094223, 0);
G2L["6"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.UIAspectRatioConstraint
G2L["7"] = Instance.new("UIAspectRatioConstraint", G2L["6"]);
G2L["7"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.UIScale
G2L["8"] = Instance.new("UIScale", G2L["6"]);
G2L["8"]["Scale"] = 0.800000011920929;

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.Line2
G2L["9"] = Instance.new("Frame", G2L["6"]);
G2L["9"]["ZIndex"] = 11;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(199, 180, 228);
G2L["9"]["BackgroundTransparency"] = 1;
G2L["9"]["Size"] = UDim2.new(0.029999999329447746, 0, 1.3070001602172852, 0);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Position"] = UDim2.new(1.0679347515106201, 0, -0.20600000023841858, 0);
G2L["9"]["Name"] = [[Line2]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.Line2.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);
G2L["a"]["CornerRadius"] = UDim.new(1111111168, 99999);

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.Line2.UIAspectRatioConstraint
G2L["b"] = Instance.new("UIAspectRatioConstraint", G2L["9"]);
G2L["b"]["AspectRatio"] = 0.09181330353021622;

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.Line
G2L["c"] = Instance.new("Frame", G2L["6"]);
G2L["c"]["ZIndex"] = -1;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundTransparency"] = 1;
G2L["c"]["Size"] = UDim2.new(0.9456523656845093, 0, 1.706521987915039, 0);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Position"] = UDim2.new(0.2212497442960739, 0, -0.369133323431015, 0);
G2L["c"]["Name"] = [[Line]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.Line.UIGradient
G2L["d"] = Instance.new("UIGradient", G2L["c"]);
G2L["d"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 1),NumberSequenceKeypoint.new(0.401, 0.11250001192092896),NumberSequenceKeypoint.new(0.500, 0.09999996423721313),NumberSequenceKeypoint.new(0.601, 0.09375),NumberSequenceKeypoint.new(1.000, 0.09999996423721313)};

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.Line.UICorner
G2L["e"] = Instance.new("UICorner", G2L["c"]);
G2L["e"]["CornerRadius"] = UDim.new(0, 3);

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.Line.UIAspectRatioConstraint
G2L["f"] = Instance.new("UIAspectRatioConstraint", G2L["c"]);
G2L["f"]["AspectRatio"] = 2.2165606021881104;

-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.LocalScript
G2L["10"] = Instance.new("LocalScript", G2L["6"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.Misc
G2L["11"] = Instance.new("TextButton", G2L["3"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["RichText"] = true;
G2L["11"]["TextScaled"] = true;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["TextSize"] = 14;
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["TextColor3"] = Color3.fromRGB(62, 60, 62);
G2L["11"]["Size"] = UDim2.new(0.38736841082572937, 0, 0.08303248882293701, 0);
G2L["11"]["Name"] = [[Misc]];
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[Misc]];
G2L["11"]["Position"] = UDim2.new(0.04636840894818306, 0, 0.2091335505247116, 0);
G2L["11"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.UIAspectRatioConstraint
G2L["12"] = Instance.new("UIAspectRatioConstraint", G2L["11"]);
G2L["12"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.UIScale
G2L["13"] = Instance.new("UIScale", G2L["11"]);
G2L["13"]["Scale"] = 0.800000011920929;

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.Line2
G2L["14"] = Instance.new("Frame", G2L["11"]);
G2L["14"]["ZIndex"] = 11;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(199, 180, 228);
G2L["14"]["BackgroundTransparency"] = 1;
G2L["14"]["Size"] = UDim2.new(0.029999999329447746, 0, 1.3070001602172852, 0);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Position"] = UDim2.new(1.0679347515106201, 0, -0.20600000023841858, 0);
G2L["14"]["Name"] = [[Line2]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.Line2.UICorner
G2L["15"] = Instance.new("UICorner", G2L["14"]);
G2L["15"]["CornerRadius"] = UDim.new(1111111168, 99999);

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.Line2.UIAspectRatioConstraint
G2L["16"] = Instance.new("UIAspectRatioConstraint", G2L["14"]);
G2L["16"]["AspectRatio"] = 0.09181330353021622;

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.Line
G2L["17"] = Instance.new("Frame", G2L["11"]);
G2L["17"]["ZIndex"] = -1;
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["BackgroundTransparency"] = 1;
G2L["17"]["Size"] = UDim2.new(0.9456523656845093, 0, 1.706521987915039, 0);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Position"] = UDim2.new(0.2212497442960739, 0, -0.369133323431015, 0);
G2L["17"]["Name"] = [[Line]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.Line.UIGradient
G2L["18"] = Instance.new("UIGradient", G2L["17"]);
G2L["18"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 1),NumberSequenceKeypoint.new(0.401, 0.11250001192092896),NumberSequenceKeypoint.new(0.500, 0.09999996423721313),NumberSequenceKeypoint.new(0.601, 0.09375),NumberSequenceKeypoint.new(1.000, 0.09999996423721313)};

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.Line.UICorner
G2L["19"] = Instance.new("UICorner", G2L["17"]);
G2L["19"]["CornerRadius"] = UDim.new(0, 3);

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.Line.UIAspectRatioConstraint
G2L["1a"] = Instance.new("UIAspectRatioConstraint", G2L["17"]);
G2L["1a"]["AspectRatio"] = 2.2165606021881104;

-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.LocalScript
G2L["1b"] = Instance.new("LocalScript", G2L["11"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.Settings
G2L["1c"] = Instance.new("TextButton", G2L["3"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["RichText"] = true;
G2L["1c"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(62, 60, 62);
G2L["1c"]["Size"] = UDim2.new(0.38736841082572937, 0, 0.08303248882293701, 0);
G2L["1c"]["Name"] = [[Settings]];
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Settings]];
G2L["1c"]["Position"] = UDim2.new(0.04636840894818306, 0, 0.33548733592033386, 0);
G2L["1c"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.UIAspectRatioConstraint
G2L["1d"] = Instance.new("UIAspectRatioConstraint", G2L["1c"]);
G2L["1d"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.UIScale
G2L["1e"] = Instance.new("UIScale", G2L["1c"]);
G2L["1e"]["Scale"] = 0.800000011920929;

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1c"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.Line2
G2L["20"] = Instance.new("Frame", G2L["1c"]);
G2L["20"]["ZIndex"] = 11;
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(199, 180, 228);
G2L["20"]["BackgroundTransparency"] = 1;
G2L["20"]["Size"] = UDim2.new(0.029999999329447746, 0, 1.3070001602172852, 0);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Position"] = UDim2.new(1.0679347515106201, 0, -0.20600000023841858, 0);
G2L["20"]["Name"] = [[Line2]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.Line2.UICorner
G2L["21"] = Instance.new("UICorner", G2L["20"]);
G2L["21"]["CornerRadius"] = UDim.new(1111111168, 99999);

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.Line2.UIAspectRatioConstraint
G2L["22"] = Instance.new("UIAspectRatioConstraint", G2L["20"]);
G2L["22"]["AspectRatio"] = 0.09181330353021622;

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.Line
G2L["23"] = Instance.new("Frame", G2L["1c"]);
G2L["23"]["ZIndex"] = -1;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["BackgroundTransparency"] = 1;
G2L["23"]["Size"] = UDim2.new(0.9456523656845093, 0, 1.706521987915039, 0);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Position"] = UDim2.new(0.2212497442960739, 0, -0.369133323431015, 0);
G2L["23"]["Name"] = [[Line]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.Line.UIGradient
G2L["24"] = Instance.new("UIGradient", G2L["23"]);
G2L["24"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 1),NumberSequenceKeypoint.new(0.401, 0.11250001192092896),NumberSequenceKeypoint.new(0.500, 0.09999996423721313),NumberSequenceKeypoint.new(0.601, 0.09375),NumberSequenceKeypoint.new(1.000, 0.09999996423721313)};

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.Line.UICorner
G2L["25"] = Instance.new("UICorner", G2L["23"]);
G2L["25"]["CornerRadius"] = UDim.new(0, 3);

-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.Line.UIAspectRatioConstraint
G2L["26"] = Instance.new("UIAspectRatioConstraint", G2L["23"]);
G2L["26"]["AspectRatio"] = 2.2165606021881104;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame
G2L["27"] = Instance.new("Frame", G2L["3"]);
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(28, 27, 28);
G2L["27"]["BackgroundTransparency"] = 1;
G2L["27"]["Size"] = UDim2.new(0.7515788674354553, 0, 1.0000001192092896, 0);
G2L["27"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["Position"] = UDim2.new(0.2484210580587387, 0, -5.508588074576437e-08, 0);
G2L["27"]["Visible"] = false;
G2L["27"]["Name"] = [[SettingsFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI
G2L["28"] = Instance.new("Frame", G2L["27"]);
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["28"]["Size"] = UDim2.new(0.9532594680786133, 0, 0.14776180684566498, 0);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Position"] = UDim2.new(0.01872924715280533, 0, 0.036101024597883224, 0);
G2L["28"]["Name"] = [[UI]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.UICorner
G2L["29"] = Instance.new("UICorner", G2L["28"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui
G2L["2a"] = Instance.new("TextButton", G2L["28"]);
G2L["2a"]["TextWrapped"] = true;
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["RichText"] = true;
G2L["2a"]["TextScaled"] = true;
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2a"]["TextSize"] = 14;
G2L["2a"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2a"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["2a"]["Size"] = UDim2.new(0.20100000500679016, 0, 0.35600000619888306, 0);
G2L["2a"]["Name"] = [[ui]];
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["Text"] = [[ui]];
G2L["2a"]["Position"] = UDim2.new(0.04800000041723251, 0, 0.2879999876022339, 0);
G2L["2a"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.UIAspectRatioConstraint
G2L["2b"] = Instance.new("UIAspectRatioConstraint", G2L["2a"]);
G2L["2b"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.FrameEffect
G2L["2c"] = Instance.new("Frame", G2L["2a"]);
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["BackgroundTransparency"] = 1;
G2L["2c"]["Size"] = UDim2.new(0.8927878141403198, 0, 1.8128408193588257, 0);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Position"] = UDim2.new(0.04801177605986595, 0, -0.37385058403015137, 0);
G2L["2c"]["Name"] = [[FrameEffect]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.FrameEffect.UICorner
G2L["2d"] = Instance.new("UICorner", G2L["2c"]);
G2L["2d"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.FrameEffect.UIAspectRatioConstraint
G2L["2e"] = Instance.new("UIAspectRatioConstraint", G2L["2c"]);
G2L["2e"]["AspectRatio"] = 1.9699199199676514;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.UICorner
G2L["2f"] = Instance.new("UICorner", G2L["2a"]);
G2L["2f"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.FrameEffect2
G2L["30"] = Instance.new("Frame", G2L["2a"]);
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(199, 180, 228);
G2L["30"]["BackgroundTransparency"] = 1;
G2L["30"]["Size"] = UDim2.new(0.6437122225761414, 0, 0.11721207201480865, 0);
G2L["30"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["Position"] = UDim2.new(0.1652238368988037, 0, 1.380385160446167, 0);
G2L["30"]["Name"] = [[FrameEffect2]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.FrameEffect2.UICorner
G2L["31"] = Instance.new("UICorner", G2L["30"]);
G2L["31"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.FrameEffect2.UIAspectRatioConstraint
G2L["32"] = Instance.new("UIAspectRatioConstraint", G2L["30"]);
G2L["32"]["AspectRatio"] = 21.967437744140625;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.LocalScript
G2L["33"] = Instance.new("LocalScript", G2L["2a"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage
G2L["34"] = Instance.new("Frame", G2L["28"]);
G2L["34"]["ZIndex"] = 11;
G2L["34"]["BorderSizePixel"] = 0;
G2L["34"]["BackgroundColor3"] = Color3.fromRGB(28, 27, 28);
G2L["34"]["Size"] = UDim2.new(1.0280542373657227, 0, 5.523329734802246, 0);
G2L["34"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["Position"] = UDim2.new(0, 0, 1, 0);
G2L["34"]["Visible"] = false;
G2L["34"]["Name"] = [[MainPage]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Themes
G2L["35"] = Instance.new("TextLabel", G2L["34"]);
G2L["35"]["TextWrapped"] = true;
G2L["35"]["ZIndex"] = 1111;
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["RichText"] = true;
G2L["35"]["TextScaled"] = true;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["TextSize"] = 14;
G2L["35"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["35"]["Size"] = UDim2.new(0.25214657187461853, 0, 0.10067114979028702, 0);
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["Text"] = [[Themes]];
G2L["35"]["Name"] = [[Themes]];
G2L["35"]["BackgroundTransparency"] = 1;
G2L["35"]["Position"] = UDim2.new(-0.0010079167550429702, 0, 0.04099995270371437, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Themes.UIAspectRatioConstraint
G2L["36"] = Instance.new("UIAspectRatioConstraint", G2L["35"]);
G2L["36"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Themes.UIScale
G2L["37"] = Instance.new("UIScale", G2L["35"]);
G2L["37"]["Scale"] = 0.6000000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Client
G2L["38"] = Instance.new("TextLabel", G2L["34"]);
G2L["38"]["TextWrapped"] = true;
G2L["38"]["ZIndex"] = 1111;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["RichText"] = true;
G2L["38"]["TextScaled"] = true;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["38"]["Size"] = UDim2.new(0.25214657187461853, 0, 0.10067114979028702, 0);
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Text"] = [[Client]];
G2L["38"]["Name"] = [[Client]];
G2L["38"]["BackgroundTransparency"] = 1;
G2L["38"]["Position"] = UDim2.new(0.4734663963317871, 0, 0.040999963879585266, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Client.UIAspectRatioConstraint
G2L["39"] = Instance.new("UIAspectRatioConstraint", G2L["38"]);
G2L["39"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Client.UIScale
G2L["3a"] = Instance.new("UIScale", G2L["38"]);
G2L["3a"]["Scale"] = 0.6000000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur
G2L["3b"] = Instance.new("TextButton", G2L["34"]);
G2L["3b"]["ZIndex"] = 111;
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["AutoButtonColor"] = false;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["3b"]["AnchorPoint"] = Vector2.new(0.5, 1);
G2L["3b"]["Size"] = UDim2.new(0.4792371392250061, 0, 0.15199999511241913, 0);
G2L["3b"]["Name"] = [[Blur]];
G2L["3b"]["Text"] = [[]];
G2L["3b"]["Position"] = UDim2.new(0.7330929040908813, 0, 0.2742052972316742, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.UIPadding
G2L["3c"] = Instance.new("UIPadding", G2L["3b"]);
G2L["3c"]["PaddingTop"] = UDim.new(0.23999999463558197, 0);
G2L["3c"]["PaddingRight"] = UDim.new(0.04500000178813934, 0);
G2L["3c"]["PaddingBottom"] = UDim.new(0.23999999463558197, 0);
G2L["3c"]["PaddingLeft"] = UDim.new(0.054999999701976776, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.UIListLayout
G2L["3d"] = Instance.new("UIListLayout", G2L["3b"]);
G2L["3d"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["3d"]["FillDirection"] = Enum.FillDirection.Horizontal;
G2L["3d"]["Padding"] = UDim.new(0, 10);
G2L["3d"]["SortOrder"] = Enum.SortOrder.LayoutOrder;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.UICorner
G2L["3e"] = Instance.new("UICorner", G2L["3b"]);
G2L["3e"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.SettingText
G2L["3f"] = Instance.new("TextLabel", G2L["3b"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(200, 200, 200);
G2L["3f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["TextSize"] = 14;
G2L["3f"]["TextColor3"] = Color3.fromRGB(162, 162, 162);
G2L["3f"]["Size"] = UDim2.new(0.5, 0, 1, 0);
G2L["3f"]["Text"] = [[Blur]];
G2L["3f"]["Name"] = [[SettingText]];
G2L["3f"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame
G2L["40"] = Instance.new("Frame", G2L["3b"]);
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["BackgroundTransparency"] = 1;
G2L["40"]["Size"] = UDim2.new(0.45412132143974304, 0, 0.9931632876396179, 0);
G2L["40"]["Position"] = UDim2.new(0.5, 0, 0.0068358187563717365, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame.ToggleFrame
G2L["41"] = Instance.new("Frame", G2L["40"]);
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(53, 50, 53);
G2L["41"]["AnchorPoint"] = Vector2.new(1, 0.5);
G2L["41"]["Size"] = UDim2.new(0.47324609756469727, 0, 1, 0);
G2L["41"]["Position"] = UDim2.new(1.000000238418579, 0, 0.5, 0);
G2L["41"]["Name"] = [[ToggleFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame.ToggleFrame.Circle
G2L["42"] = Instance.new("Frame", G2L["41"]);
G2L["42"]["BorderSizePixel"] = 0;
G2L["42"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["42"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["42"]["Size"] = UDim2.new(0.5, 0, 1, 0);
G2L["42"]["Position"] = UDim2.new(0.800000011920929, 0, 0.5, 0);
G2L["42"]["Name"] = [[Circle]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame.ToggleFrame.Circle.UICorner
G2L["43"] = Instance.new("UICorner", G2L["42"]);
G2L["43"]["CornerRadius"] = UDim.new(1, 2147483647);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame.ToggleFrame.UICorner
G2L["44"] = Instance.new("UICorner", G2L["41"]);
G2L["44"]["CornerRadius"] = UDim.new(1, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame.ToggleFrame.UIPadding
G2L["45"] = Instance.new("UIPadding", G2L["41"]);
G2L["45"]["PaddingTop"] = UDim.new(0.15000000596046448, 0);
G2L["45"]["PaddingRight"] = UDim.new(0.15000000596046448, 0);
G2L["45"]["PaddingBottom"] = UDim.new(0.15000000596046448, 0);
G2L["45"]["PaddingLeft"] = UDim.new(0.15000000596046448, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame.UIListLayout
G2L["46"] = Instance.new("UIListLayout", G2L["40"]);
G2L["46"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["46"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Right;
G2L["46"]["SortOrder"] = Enum.SortOrder.LayoutOrder;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.Frame.UIScale
G2L["47"] = Instance.new("UIScale", G2L["40"]);
G2L["47"]["Scale"] = 0.8500000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["3b"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.UIAspectRatioConstraint
G2L["49"] = Instance.new("UIAspectRatioConstraint", G2L["34"]);
G2L["49"]["AspectRatio"] = 1.5475773811340332;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color
G2L["4a"] = Instance.new("TextButton", G2L["34"]);
G2L["4a"]["TextWrapped"] = true;
G2L["4a"]["ZIndex"] = 111;
G2L["4a"]["BorderSizePixel"] = 0;
G2L["4a"]["AutoButtonColor"] = false;
G2L["4a"]["TextScaled"] = true;
G2L["4a"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["4a"]["AnchorPoint"] = Vector2.new(0.5, 1);
G2L["4a"]["Size"] = UDim2.new(0.4792371392250061, 0, 0.15199999511241913, 0);
G2L["4a"]["Name"] = [[Color]];
G2L["4a"]["Text"] = [[]];
G2L["4a"]["Position"] = UDim2.new(0.23289409279823303, 0, 0.2742052972316742, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.UIListLayout
G2L["4b"] = Instance.new("UIListLayout", G2L["4a"]);
G2L["4b"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["4b"]["FillDirection"] = Enum.FillDirection.Horizontal;
G2L["4b"]["Padding"] = UDim.new(0, 55);
G2L["4b"]["SortOrder"] = Enum.SortOrder.LayoutOrder;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.UICorner
G2L["4c"] = Instance.new("UICorner", G2L["4a"]);
G2L["4c"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.CosmicText
G2L["4d"] = Instance.new("TextLabel", G2L["4a"]);
G2L["4d"]["TextWrapped"] = true;
G2L["4d"]["TextScaled"] = true;
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(200, 200, 200);
G2L["4d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4d"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["TextSize"] = 14;
G2L["4d"]["TextColor3"] = Color3.fromRGB(162, 162, 162);
G2L["4d"]["Size"] = UDim2.new(0.4828769564628601, 0, 1.5977120399475098, 0);
G2L["4d"]["Text"] = [[Cosmic]];
G2L["4d"]["Name"] = [[CosmicText]];
G2L["4d"]["BackgroundTransparency"] = 1;
G2L["4d"]["Position"] = UDim2.new(-5.8974421790480847e-08, 0, 0.721867024898529, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.CosmicText.UIScale
G2L["4e"] = Instance.new("UIScale", G2L["4d"]);
G2L["4e"]["Scale"] = 0.800000011920929;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.CosmicText.UIAspectRatioConstraint
G2L["4f"] = Instance.new("UIAspectRatioConstraint", G2L["4d"]);
G2L["4f"]["AspectRatio"] = 4.2224884033203125;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.CosmicText.UITextSizeConstraint
G2L["50"] = Instance.new("UITextSizeConstraint", G2L["4d"]);
G2L["50"]["MaxTextSize"] = 16;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.UIStroke
G2L["51"] = Instance.new("UIStroke", G2L["4a"]);
G2L["51"]["Transparency"] = 0.8999999761581421;
G2L["51"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame
G2L["52"] = Instance.new("Frame", G2L["4a"]);
G2L["52"]["ZIndex"] = 111;
G2L["52"]["BorderSizePixel"] = 0;
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["52"]["Size"] = UDim2.new(0.36128050088882446, 0, 2.578549385070801, 0);
G2L["52"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["Position"] = UDim2.new(1.2169959545135498, 0, 0.23144882917404175, 0);
G2L["52"]["Name"] = [[ColorFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame.UIGradient
G2L["53"] = Instance.new("UIGradient", G2L["52"]);
G2L["53"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 175, 255)),ColorSequenceKeypoint.new(0.234, Color3.fromRGB(62, 156, 255)),ColorSequenceKeypoint.new(0.510, Color3.fromRGB(58, 127, 255)),ColorSequenceKeypoint.new(0.758, Color3.fromRGB(34, 75, 255)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(12, 24, 255))};

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame.UICorner
G2L["54"] = Instance.new("UICorner", G2L["52"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame.UIStroke
G2L["55"] = Instance.new("UIStroke", G2L["52"]);
G2L["55"]["Color"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["Thickness"] = 2;
G2L["55"]["Transparency"] = 0.75;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame.UIStroke.UIGradient
G2L["56"] = Instance.new("UIGradient", G2L["55"]);
G2L["56"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 175, 255)),ColorSequenceKeypoint.new(0.234, Color3.fromRGB(62, 156, 255)),ColorSequenceKeypoint.new(0.510, Color3.fromRGB(58, 127, 255)),ColorSequenceKeypoint.new(0.758, Color3.fromRGB(34, 75, 255)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(12, 24, 255))};

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame.UIScale
G2L["57"] = Instance.new("UIScale", G2L["52"]);
G2L["57"]["Scale"] = 0.75;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame.UIPadding
G2L["58"] = Instance.new("UIPadding", G2L["52"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.ColorFrame.UIAspectRatioConstraint
G2L["59"] = Instance.new("UIAspectRatioConstraint", G2L["52"]);
G2L["59"]["AspectRatio"] = 1.9574904441833496;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.UIPadding
G2L["5a"] = Instance.new("UIPadding", G2L["4a"]);
G2L["5a"]["PaddingTop"] = UDim.new(0.23999999463558197, 0);
G2L["5a"]["PaddingRight"] = UDim.new(0.04500000178813934, 0);
G2L["5a"]["PaddingBottom"] = UDim.new(0.23999999463558197, 0);
G2L["5a"]["PaddingLeft"] = UDim.new(0.054999999701976776, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.UIAspectRatioConstraint
G2L["5b"] = Instance.new("UIAspectRatioConstraint", G2L["4a"]);
G2L["5b"]["AspectRatio"] = 4.879319667816162;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.UITextSizeConstraint
G2L["5c"] = Instance.new("UITextSizeConstraint", G2L["4a"]);
G2L["5c"]["MaxTextSize"] = 8;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.LocalScript
G2L["5d"] = Instance.new("LocalScript", G2L["4a"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.UIAspectRatioConstraint
G2L["5e"] = Instance.new("UIAspectRatioConstraint", G2L["28"]);
G2L["5e"]["AspectRatio"] = 8.314522743225098;

-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UIAspectRatioConstraint
G2L["5f"] = Instance.new("UIAspectRatioConstraint", G2L["27"]);
G2L["5f"]["AspectRatio"] = 1.2888084650039673;

-- StarterGui.MainScreenGui.Frame.MainFrame.Line
G2L["60"] = Instance.new("Frame", G2L["3"]);
G2L["60"]["BorderSizePixel"] = 0;
G2L["60"]["BackgroundColor3"] = Color3.fromRGB(109, 109, 109);
G2L["60"]["BackgroundTransparency"] = 0.550000011920929;
G2L["60"]["Size"] = UDim2.new(-0.0063157896511256695, 0, -0.7545126080513, 0);
G2L["60"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["60"]["Position"] = UDim2.new(0.2484210580587387, 0, 0.8808664083480835, 0);
G2L["60"]["Name"] = [[Line]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Line.UIGradient
G2L["61"] = Instance.new("UIGradient", G2L["60"]);
G2L["61"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 1),NumberSequenceKeypoint.new(0.400, 0),NumberSequenceKeypoint.new(0.500, 0),NumberSequenceKeypoint.new(0.599, 0),NumberSequenceKeypoint.new(1.000, 1)};
G2L["61"]["Rotation"] = 90;
G2L["61"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(113, 113, 113)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(113, 113, 113))};

-- StarterGui.MainScreenGui.Frame.MainFrame.Line.UIAspectRatioConstraint
G2L["62"] = Instance.new("UIAspectRatioConstraint", G2L["60"]);
G2L["62"]["AspectRatio"] = 0.014354066923260689;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame
G2L["63"] = Instance.new("Frame", G2L["3"]);
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(28, 27, 28);
G2L["63"]["BackgroundTransparency"] = 1;
G2L["63"]["Size"] = UDim2.new(0.7515788674354553, 0, 1.0000001192092896, 0);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Position"] = UDim2.new(0.2484210580587387, 0, -5.508588074576437e-08, 0);
G2L["63"]["Visible"] = false;
G2L["63"]["Name"] = [[CombatFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI
G2L["64"] = Instance.new("Frame", G2L["63"]);
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["64"]["Size"] = UDim2.new(0.9532594680786133, 0, 0.14776180684566498, 0);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["Position"] = UDim2.new(0.01872924715280533, 0, 0.036101024597883224, 0);
G2L["64"]["Name"] = [[UI]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.UICorner
G2L["65"] = Instance.new("UICorner", G2L["64"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui
G2L["66"] = Instance.new("TextButton", G2L["64"]);
G2L["66"]["TextWrapped"] = true;
G2L["66"]["BorderSizePixel"] = 0;
G2L["66"]["RichText"] = true;
G2L["66"]["TextScaled"] = true;
G2L["66"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["TextSize"] = 14;
G2L["66"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["66"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["66"]["Size"] = UDim2.new(0.20100000500679016, 0, 0.35600000619888306, 0);
G2L["66"]["Name"] = [[ui]];
G2L["66"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["66"]["Text"] = [[ui]];
G2L["66"]["Position"] = UDim2.new(0.04800000041723251, 0, 0.2879999876022339, 0);
G2L["66"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.UIAspectRatioConstraint
G2L["67"] = Instance.new("UIAspectRatioConstraint", G2L["66"]);
G2L["67"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.FrameEffect
G2L["68"] = Instance.new("Frame", G2L["66"]);
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["68"]["BackgroundTransparency"] = 1;
G2L["68"]["Size"] = UDim2.new(0.8927878141403198, 0, 1.8128408193588257, 0);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["Position"] = UDim2.new(0.04801177605986595, 0, -0.37385058403015137, 0);
G2L["68"]["Name"] = [[FrameEffect]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.FrameEffect.UICorner
G2L["69"] = Instance.new("UICorner", G2L["68"]);
G2L["69"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.FrameEffect.UIAspectRatioConstraint
G2L["6a"] = Instance.new("UIAspectRatioConstraint", G2L["68"]);
G2L["6a"]["AspectRatio"] = 1.9699199199676514;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.UICorner
G2L["6b"] = Instance.new("UICorner", G2L["66"]);
G2L["6b"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.FrameEffect2
G2L["6c"] = Instance.new("Frame", G2L["66"]);
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(199, 180, 228);
G2L["6c"]["BackgroundTransparency"] = 1;
G2L["6c"]["Size"] = UDim2.new(0.6437122225761414, 0, 0.11721207201480865, 0);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Position"] = UDim2.new(0.1652238368988037, 0, 1.380385160446167, 0);
G2L["6c"]["Name"] = [[FrameEffect2]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.FrameEffect2.UICorner
G2L["6d"] = Instance.new("UICorner", G2L["6c"]);
G2L["6d"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.FrameEffect2.UIAspectRatioConstraint
G2L["6e"] = Instance.new("UIAspectRatioConstraint", G2L["6c"]);
G2L["6e"]["AspectRatio"] = 21.967437744140625;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.ui.LocalScript
G2L["6f"] = Instance.new("LocalScript", G2L["66"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage
G2L["70"] = Instance.new("Frame", G2L["64"]);
G2L["70"]["ZIndex"] = 11;
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(28, 27, 28);
G2L["70"]["Size"] = UDim2.new(1.0280542373657227, 0, 5.523329734802246, 0);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["Position"] = UDim2.new(0, 0, 1, 0);
G2L["70"]["Visible"] = false;
G2L["70"]["Name"] = [[MainPage]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Themes
G2L["71"] = Instance.new("TextLabel", G2L["70"]);
G2L["71"]["TextWrapped"] = true;
G2L["71"]["ZIndex"] = 1111;
G2L["71"]["BorderSizePixel"] = 0;
G2L["71"]["RichText"] = true;
G2L["71"]["TextScaled"] = true;
G2L["71"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["71"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["71"]["TextSize"] = 14;
G2L["71"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["71"]["Size"] = UDim2.new(0.25214657187461853, 0, 0.10067114979028702, 0);
G2L["71"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["Text"] = [[Auto Parry]];
G2L["71"]["Name"] = [[Themes]];
G2L["71"]["BackgroundTransparency"] = 1;
G2L["71"]["Position"] = UDim2.new(-0.0010079167550429702, 0, 0.04099995270371437, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Themes.UIAspectRatioConstraint
G2L["72"] = Instance.new("UIAspectRatioConstraint", G2L["71"]);
G2L["72"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Themes.UIScale
G2L["73"] = Instance.new("UIScale", G2L["71"]);
G2L["73"]["Scale"] = 0.6000000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto
G2L["74"] = Instance.new("TextButton", G2L["70"]);
G2L["74"]["ZIndex"] = 111;
G2L["74"]["BorderSizePixel"] = 0;
G2L["74"]["AutoButtonColor"] = false;
G2L["74"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["74"]["AnchorPoint"] = Vector2.new(0.5, 1);
G2L["74"]["Size"] = UDim2.new(0.4792371690273285, 0, 0.12727491557598114, 0);
G2L["74"]["Name"] = [[Auto]];
G2L["74"]["Text"] = [[]];
G2L["74"]["Position"] = UDim2.new(0.2386106699705124, 0, 0.24063339829444885, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.UIPadding
G2L["75"] = Instance.new("UIPadding", G2L["74"]);
G2L["75"]["PaddingTop"] = UDim.new(0.23999999463558197, 0);
G2L["75"]["PaddingRight"] = UDim.new(0.04500000178813934, 0);
G2L["75"]["PaddingBottom"] = UDim.new(0.23999999463558197, 0);
G2L["75"]["PaddingLeft"] = UDim.new(0.054999999701976776, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.UIListLayout
G2L["76"] = Instance.new("UIListLayout", G2L["74"]);
G2L["76"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["76"]["FillDirection"] = Enum.FillDirection.Horizontal;
G2L["76"]["Padding"] = UDim.new(0, 15);
G2L["76"]["SortOrder"] = Enum.SortOrder.LayoutOrder;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.UICorner
G2L["77"] = Instance.new("UICorner", G2L["74"]);
G2L["77"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.SettingText
G2L["78"] = Instance.new("TextLabel", G2L["74"]);
G2L["78"]["TextWrapped"] = true;
G2L["78"]["TextScaled"] = true;
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(200, 200, 200);
G2L["78"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["78"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["78"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["78"]["TextSize"] = 14;
G2L["78"]["TextColor3"] = Color3.fromRGB(162, 162, 162);
G2L["78"]["Size"] = UDim2.new(0.5, 0, 1, 0);
G2L["78"]["Text"] = [[Enable]];
G2L["78"]["Name"] = [[SettingText]];
G2L["78"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame
G2L["79"] = Instance.new("Frame", G2L["74"]);
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Size"] = UDim2.new(0.43901845812797546, 0, 0.922094464302063, 0);
G2L["79"]["Position"] = UDim2.new(0.5662691593170166, 0, 0.07790752500295639, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame.ToggleFrame
G2L["7a"] = Instance.new("Frame", G2L["79"]);
G2L["7a"]["BorderSizePixel"] = 0;
G2L["7a"]["BackgroundColor3"] = Color3.fromRGB(53, 50, 53);
G2L["7a"]["AnchorPoint"] = Vector2.new(1, 0.5);
G2L["7a"]["Size"] = UDim2.new(0.47324609756469727, 0, 1, 0);
G2L["7a"]["Position"] = UDim2.new(1.000000238418579, 0, 0.5, 0);
G2L["7a"]["Name"] = [[ToggleFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame.ToggleFrame.Circle
G2L["7b"] = Instance.new("Frame", G2L["7a"]);
G2L["7b"]["BorderSizePixel"] = 0;
G2L["7b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7b"]["Size"] = UDim2.new(0.5, 0, 1, 0);
G2L["7b"]["Position"] = UDim2.new(0.800000011920929, 0, 0.5, 0);
G2L["7b"]["Name"] = [[Circle]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame.ToggleFrame.Circle.UICorner
G2L["7c"] = Instance.new("UICorner", G2L["7b"]);
G2L["7c"]["CornerRadius"] = UDim.new(1, 2147483647);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame.ToggleFrame.UICorner
G2L["7d"] = Instance.new("UICorner", G2L["7a"]);
G2L["7d"]["CornerRadius"] = UDim.new(1, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame.ToggleFrame.UIPadding
G2L["7e"] = Instance.new("UIPadding", G2L["7a"]);
G2L["7e"]["PaddingTop"] = UDim.new(0.15000000596046448, 0);
G2L["7e"]["PaddingRight"] = UDim.new(0.15000000596046448, 0);
G2L["7e"]["PaddingBottom"] = UDim.new(0.15000000596046448, 0);
G2L["7e"]["PaddingLeft"] = UDim.new(0.15000000596046448, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame.UIListLayout
G2L["7f"] = Instance.new("UIListLayout", G2L["79"]);
G2L["7f"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["7f"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Right;
G2L["7f"]["SortOrder"] = Enum.SortOrder.LayoutOrder;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.Frame.UIScale
G2L["80"] = Instance.new("UIScale", G2L["79"]);
G2L["80"]["Scale"] = 0.8500000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Auto.LocalScript
G2L["81"] = Instance.new("LocalScript", G2L["74"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.UIAspectRatioConstraint
G2L["82"] = Instance.new("UIAspectRatioConstraint", G2L["70"]);
G2L["82"]["AspectRatio"] = 1.5475773811340332;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Text
G2L["83"] = Instance.new("StringValue", G2L["70"]);
G2L["83"]["Name"] = [[Text]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency
G2L["84"] = Instance.new("TextButton", G2L["70"]);
G2L["84"]["ZIndex"] = 111;
G2L["84"]["BorderSizePixel"] = 0;
G2L["84"]["AutoButtonColor"] = false;
G2L["84"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["84"]["AnchorPoint"] = Vector2.new(0.5, 1);
G2L["84"]["Size"] = UDim2.new(0.4792371690273285, 0, 0.1759324073791504, 0);
G2L["84"]["Name"] = [[Transparency]];
G2L["84"]["Text"] = [[]];
G2L["84"]["Position"] = UDim2.new(0.2386106699705124, 0, 0.43968677520751953, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.UIPadding
G2L["85"] = Instance.new("UIPadding", G2L["84"]);
G2L["85"]["PaddingTop"] = UDim.new(0.23999999463558197, 0);
G2L["85"]["PaddingRight"] = UDim.new(0.04500000178813934, 0);
G2L["85"]["PaddingBottom"] = UDim.new(0.23999999463558197, 0);
G2L["85"]["PaddingLeft"] = UDim.new(0.054999999701976776, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.UICorner
G2L["86"] = Instance.new("UICorner", G2L["84"]);
G2L["86"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.SettingText
G2L["87"] = Instance.new("TextLabel", G2L["84"]);
G2L["87"]["TextWrapped"] = true;
G2L["87"]["ZIndex"] = 1111111111;
G2L["87"]["TextScaled"] = true;
G2L["87"]["BackgroundColor3"] = Color3.fromRGB(200, 200, 200);
G2L["87"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["87"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["87"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["87"]["TextSize"] = 14;
G2L["87"]["TextColor3"] = Color3.fromRGB(162, 162, 162);
G2L["87"]["Size"] = UDim2.new(0.4357226490974426, 0, 0.7743245363235474, 0);
G2L["87"]["Text"] = [[Transparency]];
G2L["87"]["Name"] = [[SettingText]];
G2L["87"]["BackgroundTransparency"] = 1;
G2L["87"]["Position"] = UDim2.new(-0.007000000216066837, 0, -0.15700000524520874, -3);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder
G2L["88"] = Instance.new("Frame", G2L["84"]);
G2L["88"]["ZIndex"] = 1111111111;
G2L["88"]["BorderSizePixel"] = 0;
G2L["88"]["BackgroundColor3"] = Color3.fromRGB(126, 126, 126);
G2L["88"]["Size"] = UDim2.new(0, 143, 0, 4);
G2L["88"]["Position"] = UDim2.new(0.01988076977431774, 0, 0.8223862648010254, 0);
G2L["88"]["Name"] = [[WSilder]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Point
G2L["89"] = Instance.new("ImageLabel", G2L["88"]);
G2L["89"]["ZIndex"] = 4;
G2L["89"]["BorderSizePixel"] = 0;
G2L["89"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["89"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["89"]["Image"] = [[rbxassetid://1217158727]];
G2L["89"]["Size"] = UDim2.new(0, 12, 0, 12);
G2L["89"]["Name"] = [[Point]];
G2L["89"]["BackgroundTransparency"] = 1;
G2L["89"]["Position"] = UDim2.new(0, 0, 0.5, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Point.MouseOn
G2L["8a"] = Instance.new("ImageLabel", G2L["89"]);
G2L["8a"]["ZIndex"] = 4;
G2L["8a"]["BorderSizePixel"] = 0;
G2L["8a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8a"]["ImageColor3"] = Color3.fromRGB(199, 199, 199);
G2L["8a"]["ImageTransparency"] = 0.8500000238418579;
G2L["8a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["8a"]["Image"] = [[rbxassetid://1217158727]];
G2L["8a"]["Name"] = [[MouseOn]];
G2L["8a"]["BackgroundTransparency"] = 1;
G2L["8a"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Point.MouseDown
G2L["8b"] = Instance.new("ImageLabel", G2L["89"]);
G2L["8b"]["ZIndex"] = 4;
G2L["8b"]["BorderSizePixel"] = 0;
G2L["8b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8b"]["ImageTransparency"] = 0.8500000238418579;
G2L["8b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["8b"]["Image"] = [[rbxassetid://1217158727]];
G2L["8b"]["Name"] = [[MouseDown]];
G2L["8b"]["BackgroundTransparency"] = 1;
G2L["8b"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Back
G2L["8c"] = Instance.new("Frame", G2L["88"]);
G2L["8c"]["ZIndex"] = 2;
G2L["8c"]["BorderSizePixel"] = 0;
G2L["8c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8c"]["Size"] = UDim2.new(0, 0, 1, 0);
G2L["8c"]["Name"] = [[Back]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Back.UIGradient
G2L["8d"] = Instance.new("UIGradient", G2L["8c"]);
G2L["8d"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(36, 36, 36)),ColorSequenceKeypoint.new(0.839, Color3.fromRGB(223, 223, 223)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(255, 255, 255))};

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.MouseButton
G2L["8e"] = Instance.new("TextButton", G2L["88"]);
G2L["8e"]["BorderSizePixel"] = 0;
G2L["8e"]["TextTransparency"] = 1;
G2L["8e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8e"]["TextSize"] = 14;
G2L["8e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8e"]["AnchorPoint"] = Vector2.new(0, 0.5);
G2L["8e"]["Size"] = UDim2.new(1, 0, 1, 10);
G2L["8e"]["Name"] = [[MouseButton]];
G2L["8e"]["Text"] = [[]];
G2L["8e"]["Position"] = UDim2.new(0, 0, 0.5, 0);
G2L["8e"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Max
G2L["8f"] = Instance.new("IntValue", G2L["88"]);
G2L["8f"]["Value"] = 1;
G2L["8f"]["Name"] = [[Max]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.IntOnly
G2L["90"] = Instance.new("BoolValue", G2L["88"]);
G2L["90"]["Value"] = true;
G2L["90"]["Name"] = [[IntOnly]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Value
G2L["91"] = Instance.new("NumberValue", G2L["88"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.ValueLabel
G2L["92"] = Instance.new("BoolValue", G2L["88"]);
G2L["92"]["Value"] = true;
G2L["92"]["Name"] = [[ValueLabel]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.ValueLabelMultiply
G2L["93"] = Instance.new("IntValue", G2L["88"]);
G2L["93"]["Value"] = 1;
G2L["93"]["Name"] = [[ValueLabelMultiply]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.GridFrame
G2L["94"] = Instance.new("Frame", G2L["88"]);
G2L["94"]["ZIndex"] = 2;
G2L["94"]["BorderSizePixel"] = 0;
G2L["94"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["94"]["BackgroundTransparency"] = 1;
G2L["94"]["Size"] = UDim2.new(1, 0, 0, 2);
G2L["94"]["Name"] = [[GridFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.Grid
G2L["95"] = Instance.new("BoolValue", G2L["88"]);
G2L["95"]["Name"] = [[Grid]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.GridColor3
G2L["96"] = Instance.new("Color3Value", G2L["88"]);
G2L["96"]["Value"] = Color3.fromRGB(96, 96, 96);
G2L["96"]["Name"] = [[GridColor3]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.MTL_Class
G2L["97"] = Instance.new("StringValue", G2L["88"]);
G2L["97"]["Value"] = [[Silder]];
G2L["97"]["Name"] = [[MTL_Class]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.MTL_Class.PropertiesData
G2L["98"] = Instance.new("ModuleScript", G2L["97"]);
G2L["98"]["Name"] = [[PropertiesData]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.WSilder.LocalScript
G2L["99"] = Instance.new("LocalScript", G2L["88"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.Transparency.ValueAmountText
G2L["9a"] = Instance.new("TextLabel", G2L["84"]);
G2L["9a"]["ZIndex"] = 1111111111;
G2L["9a"]["BorderSizePixel"] = 0;
G2L["9a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9a"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9a"]["TextSize"] = 14;
G2L["9a"]["TextColor3"] = Color3.fromRGB(209, 209, 209);
G2L["9a"]["AnchorPoint"] = Vector2.new(0.5, 0);
G2L["9a"]["Size"] = UDim2.new(0.19032371044158936, 0, -0.47227028012275696, 28);
G2L["9a"]["Text"] = [[0]];
G2L["9a"]["Name"] = [[ValueAmountText]];
G2L["9a"]["BackgroundTransparency"] = 1;
G2L["9a"]["Position"] = UDim2.new(0.9174959659576416, 0, -0.2529999613761902, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.viewpart
G2L["9b"] = Instance.new("TextButton", G2L["70"]);
G2L["9b"]["ZIndex"] = 111;
G2L["9b"]["BorderSizePixel"] = 0;
G2L["9b"]["AutoButtonColor"] = false;
G2L["9b"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["9b"]["AnchorPoint"] = Vector2.new(0.5, 1);
G2L["9b"]["Size"] = UDim2.new(0.4792371094226837, 0, 0.12724298238754272, 0);
G2L["9b"]["Name"] = [[viewpart]];
G2L["9b"]["Text"] = [[]];
G2L["9b"]["Position"] = UDim2.new(0.2386106699705124, 0, 0.5990340709686279, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.viewpart.UIPadding
G2L["9c"] = Instance.new("UIPadding", G2L["9b"]);
G2L["9c"]["PaddingTop"] = UDim.new(0.23999999463558197, 0);
G2L["9c"]["PaddingRight"] = UDim.new(0.04500000178813934, 0);
G2L["9c"]["PaddingBottom"] = UDim.new(0.23999999463558197, 0);
G2L["9c"]["PaddingLeft"] = UDim.new(0.054999999701976776, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.viewpart.UICorner
G2L["9d"] = Instance.new("UICorner", G2L["9b"]);
G2L["9d"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.viewpart.SettingText
G2L["9e"] = Instance.new("TextLabel", G2L["9b"]);
G2L["9e"]["TextWrapped"] = true;
G2L["9e"]["ZIndex"] = 1111111111;
G2L["9e"]["TextScaled"] = true;
G2L["9e"]["BackgroundColor3"] = Color3.fromRGB(200, 200, 200);
G2L["9e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["9e"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9e"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9e"]["TextSize"] = 14;
G2L["9e"]["TextColor3"] = Color3.fromRGB(162, 162, 162);
G2L["9e"]["Size"] = UDim2.new(0.5617167949676514, 0, 1.2097716331481934, 0);
G2L["9e"]["Text"] = [[Enable View Part - ]];
G2L["9e"]["Name"] = [[SettingText]];
G2L["9e"]["BackgroundTransparency"] = 1;
G2L["9e"]["Position"] = UDim2.new(0.019525162875652313, 0, 0.036534346640110016, -3);

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.MainPage.viewpart.LocalScript
G2L["9f"] = Instance.new("LocalScript", G2L["9b"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UI.UIAspectRatioConstraint
G2L["a0"] = Instance.new("UIAspectRatioConstraint", G2L["64"]);
G2L["a0"]["AspectRatio"] = 8.314522743225098;

-- StarterGui.MainScreenGui.Frame.MainFrame.CombatFrame.UIAspectRatioConstraint
G2L["a1"] = Instance.new("UIAspectRatioConstraint", G2L["63"]);
G2L["a1"]["AspectRatio"] = 1.2888084650039673;

-- StarterGui.MainScreenGui.Frame.MainFrame.Dis
G2L["a2"] = Instance.new("TextLabel", G2L["3"]);
G2L["a2"]["TextWrapped"] = true;
G2L["a2"]["BorderSizePixel"] = 0;
G2L["a2"]["RichText"] = true;
G2L["a2"]["TextScaled"] = true;
G2L["a2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a2"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a2"]["TextSize"] = 14;
G2L["a2"]["TextColor3"] = Color3.fromRGB(145, 145, 145);
G2L["a2"]["Size"] = UDim2.new(0.14391030371189117, 0, 0.05145867168903351, 0);
G2L["a2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a2"]["Text"] = [[0]];
G2L["a2"]["Name"] = [[Dis]];
G2L["a2"]["BackgroundTransparency"] = 1;
G2L["a2"]["Position"] = UDim2.new(0.012429064139723778, 0, 0.9294048547744751, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.Dis.UIAspectRatioConstraint
G2L["a3"] = Instance.new("UIAspectRatioConstraint", G2L["a2"]);
G2L["a3"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame
G2L["a4"] = Instance.new("Frame", G2L["3"]);
G2L["a4"]["BorderSizePixel"] = 0;
G2L["a4"]["BackgroundColor3"] = Color3.fromRGB(28, 27, 28);
G2L["a4"]["BackgroundTransparency"] = 1;
G2L["a4"]["Size"] = UDim2.new(0.7515788674354553, 0, 1.0000001192092896, 0);
G2L["a4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a4"]["Position"] = UDim2.new(0.2484210580587387, 0, -5.508588074576437e-08, 0);
G2L["a4"]["Visible"] = false;
G2L["a4"]["Name"] = [[CreditFrame]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UIAspectRatioConstraint
G2L["a5"] = Instance.new("UIAspectRatioConstraint", G2L["a4"]);
G2L["a5"]["AspectRatio"] = 1.2888084650039673;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI
G2L["a6"] = Instance.new("Frame", G2L["a4"]);
G2L["a6"]["BorderSizePixel"] = 0;
G2L["a6"]["BackgroundColor3"] = Color3.fromRGB(36, 34, 36);
G2L["a6"]["Size"] = UDim2.new(0.9532594680786133, 0, 0.14776180684566498, 0);
G2L["a6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a6"]["Position"] = UDim2.new(0.01872924715280533, 0, 0.036101024597883224, 0);
G2L["a6"]["Name"] = [[UI]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.UICorner
G2L["a7"] = Instance.new("UICorner", G2L["a6"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui
G2L["a8"] = Instance.new("TextButton", G2L["a6"]);
G2L["a8"]["TextWrapped"] = true;
G2L["a8"]["BorderSizePixel"] = 0;
G2L["a8"]["RichText"] = true;
G2L["a8"]["TextScaled"] = true;
G2L["a8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a8"]["TextSize"] = 14;
G2L["a8"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a8"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["a8"]["Size"] = UDim2.new(0.20100000500679016, 0, 0.35600000619888306, 0);
G2L["a8"]["Name"] = [[ui]];
G2L["a8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a8"]["Text"] = [[ui]];
G2L["a8"]["Position"] = UDim2.new(0.04800000041723251, 0, 0.2879999876022339, 0);
G2L["a8"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.UIAspectRatioConstraint
G2L["a9"] = Instance.new("UIAspectRatioConstraint", G2L["a8"]);
G2L["a9"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.FrameEffect
G2L["aa"] = Instance.new("Frame", G2L["a8"]);
G2L["aa"]["BorderSizePixel"] = 0;
G2L["aa"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["aa"]["BackgroundTransparency"] = 1;
G2L["aa"]["Size"] = UDim2.new(0.8927878141403198, 0, 1.8128408193588257, 0);
G2L["aa"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["aa"]["Position"] = UDim2.new(0.04801177605986595, 0, -0.37385058403015137, 0);
G2L["aa"]["Name"] = [[FrameEffect]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.FrameEffect.UICorner
G2L["ab"] = Instance.new("UICorner", G2L["aa"]);
G2L["ab"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.FrameEffect.UIAspectRatioConstraint
G2L["ac"] = Instance.new("UIAspectRatioConstraint", G2L["aa"]);
G2L["ac"]["AspectRatio"] = 1.9699199199676514;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.UICorner
G2L["ad"] = Instance.new("UICorner", G2L["a8"]);
G2L["ad"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.FrameEffect2
G2L["ae"] = Instance.new("Frame", G2L["a8"]);
G2L["ae"]["BorderSizePixel"] = 0;
G2L["ae"]["BackgroundColor3"] = Color3.fromRGB(199, 180, 228);
G2L["ae"]["BackgroundTransparency"] = 1;
G2L["ae"]["Size"] = UDim2.new(0.6437122225761414, 0, 0.11721207201480865, 0);
G2L["ae"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ae"]["Position"] = UDim2.new(0.1652238368988037, 0, 1.380385160446167, 0);
G2L["ae"]["Name"] = [[FrameEffect2]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.FrameEffect2.UICorner
G2L["af"] = Instance.new("UICorner", G2L["ae"]);
G2L["af"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.FrameEffect2.UIAspectRatioConstraint
G2L["b0"] = Instance.new("UIAspectRatioConstraint", G2L["ae"]);
G2L["b0"]["AspectRatio"] = 21.967437744140625;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.ui.LocalScript
G2L["b1"] = Instance.new("LocalScript", G2L["a8"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage
G2L["b2"] = Instance.new("Frame", G2L["a6"]);
G2L["b2"]["ZIndex"] = 11;
G2L["b2"]["BorderSizePixel"] = 0;
G2L["b2"]["BackgroundColor3"] = Color3.fromRGB(28, 27, 28);
G2L["b2"]["Size"] = UDim2.new(1.0280542373657227, 0, 5.523329734802246, 0);
G2L["b2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b2"]["Position"] = UDim2.new(0, 0, 1, 0);
G2L["b2"]["Visible"] = false;
G2L["b2"]["Name"] = [[MainPage]];

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.UIAspectRatioConstraint
G2L["b3"] = Instance.new("UIAspectRatioConstraint", G2L["b2"]);
G2L["b3"]["AspectRatio"] = 1.5475773811340332;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer
G2L["b4"] = Instance.new("TextLabel", G2L["b2"]);
G2L["b4"]["TextWrapped"] = true;
G2L["b4"]["ZIndex"] = 1111;
G2L["b4"]["BorderSizePixel"] = 0;
G2L["b4"]["RichText"] = true;
G2L["b4"]["TextScaled"] = true;
G2L["b4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b4"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b4"]["TextSize"] = 14;
G2L["b4"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["b4"]["Size"] = UDim2.new(0.25214657187461853, 0, 0.10067114979028702, 0);
G2L["b4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b4"]["Text"] = [[Developer:]];
G2L["b4"]["Name"] = [[Developer]];
G2L["b4"]["BackgroundTransparency"] = 1;
G2L["b4"]["Position"] = UDim2.new(-0.0010079167550429702, 0, 0.04099995270371437, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.UIScale
G2L["b5"] = Instance.new("UIScale", G2L["b4"]);
G2L["b5"]["Scale"] = 0.6000000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.UIAspectRatioConstraint
G2L["b6"] = Instance.new("UIAspectRatioConstraint", G2L["b4"]);
G2L["b6"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.Username
G2L["b7"] = Instance.new("TextLabel", G2L["b4"]);
G2L["b7"]["TextWrapped"] = true;
G2L["b7"]["ZIndex"] = 1111;
G2L["b7"]["BorderSizePixel"] = 0;
G2L["b7"]["RichText"] = true;
G2L["b7"]["TextScaled"] = true;
G2L["b7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b7"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b7"]["TextSize"] = 14;
G2L["b7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b7"]["Size"] = UDim2.new(2.216944694519043, 0, 4.317519664764404, 0);
G2L["b7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b7"]["Text"] = [[DevTravDYT]];
G2L["b7"]["Name"] = [[Username]];
G2L["b7"]["BackgroundTransparency"] = 1;
G2L["b7"]["Position"] = UDim2.new(-0.0010090151336044073, 0, 0.9648312926292419, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.Username.UIScale
G2L["b8"] = Instance.new("UIScale", G2L["b7"]);
G2L["b8"]["Scale"] = 0.6000000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.Username.UIAspectRatioConstraint
G2L["b9"] = Instance.new("UIAspectRatioConstraint", G2L["b7"]);
G2L["b9"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer
G2L["ba"] = Instance.new("TextLabel", G2L["b2"]);
G2L["ba"]["TextWrapped"] = true;
G2L["ba"]["ZIndex"] = 1111;
G2L["ba"]["BorderSizePixel"] = 0;
G2L["ba"]["RichText"] = true;
G2L["ba"]["TextScaled"] = true;
G2L["ba"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ba"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ba"]["TextSize"] = 14;
G2L["ba"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["ba"]["Size"] = UDim2.new(0.25214657187461853, 0, 0.10067114979028702, 0);
G2L["ba"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ba"]["Text"] = [[Owner:]];
G2L["ba"]["Name"] = [[Developer]];
G2L["ba"]["BackgroundTransparency"] = 1;
G2L["ba"]["Position"] = UDim2.new(0.4216596782207489, 0, 0.050836142152547836, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.UIScale
G2L["bb"] = Instance.new("UIScale", G2L["ba"]);
G2L["bb"]["Scale"] = 0.6000000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.UIAspectRatioConstraint
G2L["bc"] = Instance.new("UIAspectRatioConstraint", G2L["ba"]);
G2L["bc"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.Username
G2L["bd"] = Instance.new("TextLabel", G2L["ba"]);
G2L["bd"]["TextWrapped"] = true;
G2L["bd"]["ZIndex"] = 1111;
G2L["bd"]["BorderSizePixel"] = 0;
G2L["bd"]["RichText"] = true;
G2L["bd"]["TextScaled"] = true;
G2L["bd"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["bd"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["bd"]["TextSize"] = 14;
G2L["bd"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["bd"]["Size"] = UDim2.new(2.216944694519043, 0, 4.317519664764404, 0);
G2L["bd"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["bd"]["Text"] = [[B1tcoinberry]];
G2L["bd"]["Name"] = [[Username]];
G2L["bd"]["BackgroundTransparency"] = 1;
G2L["bd"]["Position"] = UDim2.new(-0.0010090151336044073, 0, 0.9648312926292419, 0);

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.Username.UIScale
G2L["be"] = Instance.new("UIScale", G2L["bd"]);
G2L["be"]["Scale"] = 0.6000000238418579;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.MainPage.Developer.Username.UIAspectRatioConstraint
G2L["bf"] = Instance.new("UIAspectRatioConstraint", G2L["bd"]);
G2L["bf"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.CreditFrame.UI.UIAspectRatioConstraint
G2L["c0"] = Instance.new("UIAspectRatioConstraint", G2L["a6"]);
G2L["c0"]["AspectRatio"] = 8.314522743225098;

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit
G2L["c1"] = Instance.new("TextButton", G2L["3"]);
G2L["c1"]["TextWrapped"] = true;
G2L["c1"]["BorderSizePixel"] = 0;
G2L["c1"]["RichText"] = true;
G2L["c1"]["TextStrokeColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c1"]["TextScaled"] = true;
G2L["c1"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c1"]["TextSize"] = 14;
G2L["c1"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c1"]["TextColor3"] = Color3.fromRGB(62, 60, 62);
G2L["c1"]["Size"] = UDim2.new(0.38736841082572937, 0, 0.08303248882293701, 0);
G2L["c1"]["Name"] = [[Credit]];
G2L["c1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c1"]["Text"] = [[Credit]];
G2L["c1"]["Position"] = UDim2.new(0.04636838659644127, 0, 0.4639310836791992, 0);
G2L["c1"]["BackgroundTransparency"] = 1;

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.UIAspectRatioConstraint
G2L["c2"] = Instance.new("UIAspectRatioConstraint", G2L["c1"]);
G2L["c2"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.UIScale
G2L["c3"] = Instance.new("UIScale", G2L["c1"]);
G2L["c3"]["Scale"] = 0.800000011920929;

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.LocalScript
G2L["c4"] = Instance.new("LocalScript", G2L["c1"]);


-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.Line2
G2L["c5"] = Instance.new("Frame", G2L["c1"]);
G2L["c5"]["ZIndex"] = 11;
G2L["c5"]["BorderSizePixel"] = 0;
G2L["c5"]["BackgroundColor3"] = Color3.fromRGB(199, 180, 228);
G2L["c5"]["BackgroundTransparency"] = 1;
G2L["c5"]["Size"] = UDim2.new(0.029999999329447746, 0, 1.3070001602172852, 0);
G2L["c5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c5"]["Position"] = UDim2.new(1.0679347515106201, 0, -0.20600000023841858, 0);
G2L["c5"]["Name"] = [[Line2]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.Line2.UICorner
G2L["c6"] = Instance.new("UICorner", G2L["c5"]);
G2L["c6"]["CornerRadius"] = UDim.new(1111111168, 99999);

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.Line2.UIAspectRatioConstraint
G2L["c7"] = Instance.new("UIAspectRatioConstraint", G2L["c5"]);
G2L["c7"]["AspectRatio"] = 0.09181330353021622;

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.Line
G2L["c8"] = Instance.new("Frame", G2L["c1"]);
G2L["c8"]["ZIndex"] = -1;
G2L["c8"]["BorderSizePixel"] = 0;
G2L["c8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c8"]["BackgroundTransparency"] = 1;
G2L["c8"]["Size"] = UDim2.new(0.9456523656845093, 0, 1.706521987915039, 0);
G2L["c8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c8"]["Position"] = UDim2.new(0.2212497442960739, 0, -0.369133323431015, 0);
G2L["c8"]["Name"] = [[Line]];

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.Line.UIGradient
G2L["c9"] = Instance.new("UIGradient", G2L["c8"]);
G2L["c9"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 1),NumberSequenceKeypoint.new(0.401, 0.11250001192092896),NumberSequenceKeypoint.new(0.500, 0.09999996423721313),NumberSequenceKeypoint.new(0.601, 0.09375),NumberSequenceKeypoint.new(1.000, 0.09999996423721313)};

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.Line.UICorner
G2L["ca"] = Instance.new("UICorner", G2L["c8"]);
G2L["ca"]["CornerRadius"] = UDim.new(0, 3);

-- StarterGui.MainScreenGui.Frame.MainFrame.Credit.Line.UIAspectRatioConstraint
G2L["cb"] = Instance.new("UIAspectRatioConstraint", G2L["c8"]);
G2L["cb"]["AspectRatio"] = 2.2165606021881104;

-- StarterGui.MainScreenGui.Frame.UICorner
G2L["cc"] = Instance.new("UICorner", G2L["2"]);
G2L["cc"]["CornerRadius"] = UDim.new(0, 15);

-- StarterGui.MainScreenGui.Frame.UIStroke
G2L["cd"] = Instance.new("UIStroke", G2L["2"]);
G2L["cd"]["Transparency"] = 0.7200000286102295;

-- StarterGui.MainScreenGui.Frame.Icon
G2L["ce"] = Instance.new("ImageLabel", G2L["2"]);
G2L["ce"]["BorderSizePixel"] = 0;
G2L["ce"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ce"]["ImageTransparency"] = 0.029999999329447746;
G2L["ce"]["Image"] = [[rbxassetid://663710708]];
G2L["ce"]["Size"] = UDim2.new(0.2109704464673996, 0, 0.33557048439979553, 0);
G2L["ce"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ce"]["Name"] = [[Icon]];
G2L["ce"]["BackgroundTransparency"] = 1;
G2L["ce"]["Position"] = UDim2.new(0.030000001192092896, 0, 0.010067113675177097, 2);

-- StarterGui.MainScreenGui.Frame.Icon.UIScale
G2L["cf"] = Instance.new("UIScale", G2L["ce"]);
G2L["cf"]["Scale"] = 0.30000001192092896;

-- StarterGui.MainScreenGui.Frame.Icon.UIAspectRatioConstraint
G2L["d0"] = Instance.new("UIAspectRatioConstraint", G2L["ce"]);


-- StarterGui.MainScreenGui.Frame.Icon.UIGradient
G2L["d1"] = Instance.new("UIGradient", G2L["ce"]);
G2L["d1"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 1),NumberSequenceKeypoint.new(0.401, 0.11250001192092896),NumberSequenceKeypoint.new(0.500, 0.09999996423721313),NumberSequenceKeypoint.new(0.601, 0.09375),NumberSequenceKeypoint.new(1.000, 0.09999996423721313)};
G2L["d1"]["Rotation"] = -34;
G2L["d1"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(192, 192, 192)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(255, 255, 255))};

-- StarterGui.MainScreenGui.Frame.Icon.UICosmic
G2L["d2"] = Instance.new("UIGradient", G2L["ce"]);
G2L["d2"]["Enabled"] = false;
G2L["d2"]["Name"] = [[UICosmic]];
G2L["d2"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 175, 255)),ColorSequenceKeypoint.new(0.234, Color3.fromRGB(62, 156, 255)),ColorSequenceKeypoint.new(0.510, Color3.fromRGB(58, 127, 255)),ColorSequenceKeypoint.new(0.758, Color3.fromRGB(34, 75, 255)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(12, 24, 255))};

-- StarterGui.MainScreenGui.Frame.Layer
G2L["d3"] = Instance.new("ImageLabel", G2L["2"]);
G2L["d3"]["ZIndex"] = -10;
G2L["d3"]["BorderSizePixel"] = 0;
G2L["d3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d3"]["ImageTransparency"] = 0.6800000071525574;
G2L["d3"]["Image"] = [[rbxassetid://12162975974]];
G2L["d3"]["Size"] = UDim2.new(0.9999999403953552, 0, 1, 0);
G2L["d3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d3"]["Name"] = [[Layer]];
G2L["d3"]["BackgroundTransparency"] = 1;
G2L["d3"]["Position"] = UDim2.new(3.2191536547543365e-08, 0, 0, 0);

-- StarterGui.MainScreenGui.Frame.Layer.UIGradient
G2L["d4"] = Instance.new("UIGradient", G2L["d3"]);
G2L["d4"]["Rotation"] = 90;
G2L["d4"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(209, 209, 209)),ColorSequenceKeypoint.new(0.801, Color3.fromRGB(19, 19, 19)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};

-- StarterGui.MainScreenGui.Frame.Layer.UICorner
G2L["d5"] = Instance.new("UICorner", G2L["d3"]);
G2L["d5"]["CornerRadius"] = UDim.new(0, 15);

-- StarterGui.MainScreenGui.Frame.LocalScript
G2L["d6"] = Instance.new("LocalScript", G2L["2"]);


-- StarterGui.MainScreenGui.Frame.UIAspectRatioConstraint
G2L["d7"] = Instance.new("UIAspectRatioConstraint", G2L["2"]);
G2L["d7"]["AspectRatio"] = 1.5906040668487549;

-- StarterGui.MainScreenGui.Frame.UIScale
G2L["d8"] = Instance.new("UIScale", G2L["2"]);
G2L["d8"]["Scale"] = 0.8999999761581421;

-- StarterGui.MainScreenGui.Frame.Title
G2L["d9"] = Instance.new("TextLabel", G2L["2"]);
G2L["d9"]["TextWrapped"] = true;
G2L["d9"]["BorderSizePixel"] = 0;
G2L["d9"]["RichText"] = true;
G2L["d9"]["TextScaled"] = true;
G2L["d9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d9"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d9"]["TextSize"] = 14;
G2L["d9"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["d9"]["Size"] = UDim2.new(0.3122362792491913, 0, 0.10067114979028702, 0);
G2L["d9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d9"]["Text"] = [[Visual V.1.0 BETA]];
G2L["d9"]["Name"] = [[Title]];
G2L["d9"]["BackgroundTransparency"] = 1;
G2L["d9"]["Position"] = UDim2.new(0.10999999940395355, 0, 0.017000000923871994, 0);

-- StarterGui.MainScreenGui.Frame.Title.UIAspectRatioConstraint
G2L["da"] = Instance.new("UIAspectRatioConstraint", G2L["d9"]);
G2L["da"]["AspectRatio"] = 4;

-- StarterGui.MainScreenGui.Frame.Title.UICosmic
G2L["db"] = Instance.new("UIGradient", G2L["d9"]);
G2L["db"]["Enabled"] = false;
G2L["db"]["Name"] = [[UICosmic]];
G2L["db"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 175, 255)),ColorSequenceKeypoint.new(0.234, Color3.fromRGB(62, 156, 255)),ColorSequenceKeypoint.new(0.510, Color3.fromRGB(58, 127, 255)),ColorSequenceKeypoint.new(0.758, Color3.fromRGB(34, 75, 255)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(12, 24, 255))};

-- StarterGui.MainScreenGui.Frame.BlackList
G2L["dc"] = Instance.new("LocalScript", G2L["2"]);
G2L["dc"]["Name"] = [[BlackList]];

-- StarterGui.MainScreenGui.FPS
G2L["dd"] = Instance.new("TextLabel", G2L["1"]);
G2L["dd"]["TextWrapped"] = true;
G2L["dd"]["BorderSizePixel"] = 0;
G2L["dd"]["RichText"] = true;
G2L["dd"]["TextScaled"] = true;
G2L["dd"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["dd"]["FontFace"] = Font.new([[rbxasset://fonts/families/GothamSSm.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["dd"]["TextSize"] = 14;
G2L["dd"]["TextColor3"] = Color3.fromRGB(228, 228, 228);
G2L["dd"]["Size"] = UDim2.new(0.12601430714130402, 0, 0.026477592065930367, 0);
G2L["dd"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["dd"]["Text"] = [[0]];
G2L["dd"]["Name"] = [[FPS]];
G2L["dd"]["BackgroundTransparency"] = 1;
G2L["dd"]["Position"] = UDim2.new(0.061219509690999985, 0, 0.19603227078914642, 0);

-- StarterGui.MainScreenGui.FPS.LocalScript
G2L["de"] = Instance.new("LocalScript", G2L["dd"]);


-- StarterGui.MainScreenGui.LocalScript
G2L["df"] = Instance.new("LocalScript", G2L["1"]);


-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["98"]] = {
Closure = function()
    local script = G2L["98"];
local Main = script.Parent.Parent
local Properties = {
	GetPropertiesDataModuleRoot = function()
		return script
	end;
	PropertieName = {
		Properties = {
			"ClassName";
			"Parent";
			"Name";
			"AbsolutePosition";
			"AbsoluteSize";
			"AnchorPoint";
			"Visible";
			"Size";
			"Position";
			"SilderBackgroundColor3";
			"SilderColor3";
			"SilderValue";
			"SilderMax";
			"SilderIntOnly";
			"SilderGrid";
			"SilderGridColor3";
			"ValueLabelVisible";
			"ValueLabelTextColor3";
			"ValueLabelMultiply";
		};
		Event = {
			"MouseClickEvent";
		};
	};
	PropertieType = {
		ClassName="string";
		Parent="Instance";
		Name="string";
		AbsolutePosition="Vector2"; 
		AbsoluteSize="Vector2";
		AnchorPoint="Vector2";
		Visible="boolean";
		SilderBackgroundColor3="Color3";
		SilderColor3="Color3";
		SilderValue="number";
		SilderMax="number";
		SilderIntOnly="boolean";
		SilderGrid="boolean";
		SilderGridColor3="Color3";
		ValueLabelVisible="boolean";
		ValueLabelTextColor3="Color3";
		ValueLabelMultiply="number";
	};
	ReadOnry = {
		"ClassName";
		"AbsolutePosition";
		"AbsoluteSize";
	};
	StyleList = {
		"Contained";
		"Outlined";
		"Text";
	};
	ClassName = function()
		return script.Parent.Value -- Read Onry data
	end;
	Parent = function(Value)
		if Value == nil then
			return Main.Parent --Read
		else
			Main.Parent = Value --write
		end
	end;
	Name = function(Value)
		if Value == nil then
			return Main.Name
		else
			Main.Name = Value
		end
	end;
	AbsolutePosition = function(Value)
		return Main.AbsolutePosition
	end;
	AbsoluteSize = function(Value)
		return Main.AbsoluteSize
	end;
	AnchorPoint = function(Value)
		if Value == nil then
			return Main.AnchorPoint
		else
			Main.AnchorPoint = Value
		end
	end;
	Visible = function(Value)
		if Value == nil then
			return Main.Visible
		else
			Main.Visible = Value
		end
	end;
	Size = function(Value)
		if Value == nil then
			return Main.Size
		else
			Main.Size = Value
		end
	end;
	Position = function(Value)
		if Value == nil then
			return Main.Position
		else
			Main.Position = Value
		end
	end;
	SilderBackgroundColor3 = function(Value)
		if Value == nil then
			return Main.BackgroundColor3
		else
			Main.BackgroundColor3 = Value
		end
	end; 
	SilderColor3 = function(Value)
		if Value == nil then
			return Main.Back.BackgroundColor3
		else
			Main.Back.BackgroundColor3 = Value
			Main.Point.ImageColor3 = Value
			Main.Point.MouseDown.ImageColor3 = Value
			Main.Point.MouseOn.ImageColor3 = Value
			Main.Point.ValueLabel.ImageColor3 = Value
		end
	end;
	SilderValue = function(Value)
		if Value == nil then
			return Main.Value.Value
		else
			Main.Value.Value = Value
		end
	end;
	SilderMax = function(Value)
		if Value == nil then
			return Main.Max.Value
		else
			Main.Max.Value = Value
		end
	end;
	SilderIntOnly = function(Value)
		if Value == nil then
			return Main.IntOnly.Value
		else
			Main.IntOnly.Value = Value
		end
	end;
	SilderGrid = function(Value)
		if Value == nil then
			return Main.Grid.Value
		else
			Main.Grid.Value = Value
		end
	end;
	SilderGridColor3 = function(Value)
		if Value == nil then
			return Main.GridColor3.Value
		else
			Main.GridColor3.Value = Value
		end
	end;
	ValueLabelVisible = function(Value)
		if Value == nil then
			return Main.ValueLabel.Value
		else
			Main.ValueLabel.Value = Value
		end
	end;
	ValueLabelTextColor3 = function(Value)
		if Value == nil then
			return Main.Point.ValueLabel.Text.TextColor3
		else
			Main.Point.ValueLabel.Text.TextColor3 = Value
		end
	end;
	ValueLabelMultiply = function(Value)
		if Value == nil then
			return Main.ValueLabelMultiply.Value
		else
			Main.ValueLabelMultiply.Value = Value
		end
	end;
}
return Properties

end;
};
-- StarterGui.MainScreenGui.Frame.MainFrame.Combat.LocalScript
local function C_10()
local script = G2L["10"];
	local Frame1 = script.Parent.Line
	local Frame2 = script.Parent.Line2
	local OtherFrame1 = script.Parent.Parent.Misc.Line
	local OtherFrame2 = script.Parent.Parent.Misc.Line2
	local OtherFrame3 = script.Parent.Parent.Settings.Line
	local OtherFrame4 = script.Parent.Parent.Settings.Line2
	local OtherFrame5 = script.Parent.Parent.Credit.Line
	local OtherFrame6 = script.Parent.Parent.Credit.Line2
	local l__TweenService__14 = game:GetService("TweenService");
	local onoff = true
	
	local tweenInfo = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween = l__TweenService__14:Create(Frame1, tweenInfo, {Transparency = 0.8})
	
	local tweenInfo2 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween2 = l__TweenService__14:Create(Frame2, tweenInfo2, {Transparency = 0})
	--
	local tweenInfo3 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween3 = l__TweenService__14:Create(OtherFrame2, tweenInfo3, {Transparency = 1})
	
	local tweenInfo4 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween4 = l__TweenService__14:Create(OtherFrame1, tweenInfo4, {Transparency = 1})
	
	local rbasdadwrbasdadwrbasdadw = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local rbasdadwrbasdadwrbasdadwrbasdadwrbasdadw = l__TweenService__14:Create(OtherFrame5, rbasdadwrbasdadwrbasdadw, {Transparency = 1})
	
	local brsdaodhawotasd = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local brsdaodhawotasdbrsdaodhawotasd = l__TweenService__14:Create(OtherFrame6, brsdaodhawotasd, {Transparency = 1})
	--
	local tweenInfo5 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween5 = l__TweenService__14:Create(script.Parent, tweenInfo5, {TextColor3 = Color3.fromRGB(255, 255, 255)})
	--
	local tweenInfo6 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween6 = l__TweenService__14:Create(script.Parent.Parent.Misc, tweenInfo6, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	--
	local bruhdaminfo2 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local ayemama = l__TweenService__14:Create(script.Parent, bruhdaminfo2, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	
	local tweenInfo7 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween7 = l__TweenService__14:Create(script.Parent.Parent.Settings, tweenInfo7, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	local tweenInfo7tweenInfo7tweenInfo7tweenInfo7 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween7tween7tween7 = l__TweenService__14:Create(script.Parent.Parent.Credit, tweenInfo7tweenInfo7tweenInfo7tweenInfo7, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	--
	local tweenInfo31 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween31 = l__TweenService__14:Create(OtherFrame3, tweenInfo31, {Transparency = 1})
	local tweenInfo31tweenInfo31tweenInfo31tweenInfo31tweenInfo31 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween31Tween31Tween31Tween31Tween31Tween31 = l__TweenService__14:Create(script.Parent.Parent.Credit.Line, tweenInfo31tweenInfo31tweenInfo31tweenInfo31tweenInfo31, {Transparency = 1})
	
	local tweenInfo41 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween41 = l__TweenService__14:Create(OtherFrame4, tweenInfo41, {Transparency = 1})
	
	local Testinginfo = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local yoama = l__TweenService__14:Create(Frame1, Testinginfo, {Transparency = 1})
	
	local Testinginfo2 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local yoama2 = l__TweenService__14:Create(Frame2, Testinginfo2, {Transparency = 1})
	
	local Testinginfo2Testinginfo2Testinginfo2 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local yoama2yoama2yoama2 = l__TweenService__14:Create(script.Parent.Parent.Credit.Line2, Testinginfo2Testinginfo2Testinginfo2, {Transparency = 1})
	
	script.Parent.MouseButton1Click:Connect(function()
		if onoff == true  then
		Tween:Play()
		Tween2:Play()
		Tween3:Play()
		Tween4:Play()
		tween5:Play()
		tween6:Play()
		tween7:Play()
		Tween31:Play()
			Tween41:Play()
			rbasdadwrbasdadwrbasdadwrbasdadwrbasdadw:Play()
			brsdaodhawotasdbrsdaodhawotasd:Play()
			tween7tween7tween7:Play()
			Tween31Tween31Tween31Tween31Tween31Tween31:Play()
			yoama2yoama2yoama2:Play()
			script.Parent.Parent.SettingsFrame.Visible = false
			script.Parent.Parent.SettingsFrame.UI.ui.FrameEffect.Transparency = 1
			script.Parent.Parent.SettingsFrame.UI.ui.FrameEffect2.Transparency = 1
			script.Parent.Parent.SettingsFrame.UI.MainPage.Visible = false
			script.Parent.Parent.CreditFrame.Visible = false
			script.Parent.Parent.CreditFrame.UI.ui.FrameEffect.Transparency = 1
			script.Parent.Parent.CreditFrame.UI.ui.FrameEffect2.Transparency = 1
			script.Parent.Parent.CreditFrame.UI.MainPage.Visible = false
		script.Parent.Parent.CombatFrame.Visible = true
		onoff = false
		else
			wait(0.2)
			onoff = true
			ayemama:Play()
		yoama:Play()
		yoama2:Play()
		script.Parent.Parent.CombatFrame.Visible = false
		end
	end)
end;
task.spawn(C_10);
-- StarterGui.MainScreenGui.Frame.MainFrame.Misc.LocalScript
local function C_1b()
local script = G2L["1b"];
	local Frame1 = script.Parent.Line
	local Frame2 = script.Parent.Line2
	local OtherFrame1 = script.Parent.Parent.Combat.Line
	local OtherFrame2 = script.Parent.Parent.Combat.Line2
	local OtherFrame3 = script.Parent.Parent.Settings.Line
	local OtherFrame4 = script.Parent.Parent.Settings.Line2
	
	local OtherFrame5 = script.Parent.Parent.Credit.Line
	local OtherFrame6 = script.Parent.Parent.Credit.Line2
	local onoff = true
	
	local l__TweenService__14 = game:GetService("TweenService");
	
	local tweenInfo = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween = l__TweenService__14:Create(Frame1, tweenInfo, {Transparency = 0.8})
	
	local tweenInfo2 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween2 = l__TweenService__14:Create(Frame2, tweenInfo2, {Transparency = 0})
	--
	local tweenInfo3 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween3 = l__TweenService__14:Create(OtherFrame2, tweenInfo3, {Transparency = 1})
	
	local tweenInfo4 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween4 = l__TweenService__14:Create(OtherFrame1, tweenInfo4, {Transparency = 1})
	local twadsawrasda1 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local sadasdadwa2 = l__TweenService__14:Create(script.Parent.Line, twadsawrasda1, {Transparency = 1})
	--
	local tweenInfo5 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween5 = l__TweenService__14:Create(script.Parent, tweenInfo5, {TextColor3 = Color3.fromRGB(255, 255, 255)})
	--
	local tweenInfo6 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween6 = l__TweenService__14:Create(script.Parent.Parent.Combat, tweenInfo6, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	--
	local tweenInfo7 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween7 = l__TweenService__14:Create(script.Parent.Parent.Settings, tweenInfo7, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	
	local tweenInfo31 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween31 = l__TweenService__14:Create(OtherFrame3, tweenInfo31, {Transparency = 1})
	
	local asdasdasdasdawadsas = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local aasdawaretgasd = l__TweenService__14:Create(script.Parent.Line2, asdasdasdasdawadsas, {Transparency = 1})
	
	local tweenInfo41 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween41 = l__TweenService__14:Create(OtherFrame4, tweenInfo41, {Transparency = 1})
	
	local tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween41Tween41Tween41Tween41Tween41Tween41Tween41Tween41 = l__TweenService__14:Create(OtherFrame6, tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41, {Transparency = 1})
	
	local tweenInfo41tweenInfo41tweenInfo41 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween41Tween41Tween41Tween41 = l__TweenService__14:Create(OtherFrame5, tweenInfo41tweenInfo41tweenInfo41, {Transparency = 1})
	
	local bruhdaminfo2 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local ayemama = l__TweenService__14:Create(script.Parent, bruhdaminfo2, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	
	
	local bruhdaminfo2bruhdaminfo2bruhdaminfo2bruhdaminfo2bruhdaminfo2 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local ayemamaayemamaayemamaayemama = l__TweenService__14:Create(script.Parent.Parent.Credit, bruhdaminfo2bruhdaminfo2bruhdaminfo2bruhdaminfo2bruhdaminfo2, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	
	
	
	script.Parent.MouseButton1Click:Connect(function()
		if onoff == true then
		Tween:Play()
		Tween2:Play()
		Tween3:Play()
		Tween4:Play()
		tween5:Play()
		tween6:Play()
		tween7:Play()
		Tween31:Play()
			Tween41:Play()
			Tween41Tween41Tween41Tween41:Play()
			ayemamaayemamaayemamaayemama:Play()
			Tween41Tween41Tween41Tween41Tween41Tween41Tween41Tween41:Play()
		script.Parent.Parent.SettingsFrame.Visible = false
		script.Parent.Parent.SettingsFrame.UI.ui.FrameEffect.Transparency = 1
		script.Parent.Parent.SettingsFrame.UI.ui.FrameEffect2.Transparency = 1
		script.Parent.Parent.SettingsFrame.UI.MainPage.Visible = false
		script.Parent.Parent.CombatFrame.Visible = false
		script.Parent.Parent.CombatFrame.UI.ui.FrameEffect.Transparency = 1
		script.Parent.Parent.CombatFrame.UI.ui.FrameEffect2.Transparency = 1
			script.Parent.Parent.CombatFrame.UI.MainPage.Visible = false
			onoff = false
		else
			wait(0.2)
			onoff = true
			ayemama:Play()
			sadasdadwa2:Play()
			aasdawaretgasd:Play()
		end
	end)
end;
task.spawn(C_1b);
-- StarterGui.MainScreenGui.Frame.MainFrame.Settings.LocalScript
local function C_1f()
local script = G2L["1f"];
	local onoff = true
	local Frame1 = script.Parent.Line
	local Frame2 = script.Parent.Line2
	local OtherFrame1 = script.Parent.Parent.Misc.Line
	local OtherFrame2 = script.Parent.Parent.Misc.Line2
	local OtherFrame3 = script.Parent.Parent.Combat.Line
	local OtherFrame4 = script.Parent.Parent.Combat.Line2
	local l__TweenService__14 = game:GetService("TweenService");
	
	local Testinginfo = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local yoama = l__TweenService__14:Create(Frame1, Testinginfo, {Transparency = 1})
	
	local Testinginfo2 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local yoama2 = l__TweenService__14:Create(Frame2, Testinginfo2, {Transparency = 1})
	--
	
	local tweenInfo = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween = l__TweenService__14:Create(Frame1, tweenInfo, {Transparency = 0.8})
	
	local tweenInfo2 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween2 = l__TweenService__14:Create(Frame2, tweenInfo2, {Transparency = 0})
	--
	local tweenInfo3 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween3 = l__TweenService__14:Create(OtherFrame2, tweenInfo3, {Transparency = 1})
	
	local tweenInfo4 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween4 = l__TweenService__14:Create(OtherFrame1, tweenInfo4, {Transparency = 1})
	--
	local tweenInfo5 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween5 = l__TweenService__14:Create(script.Parent, tweenInfo5, {TextColor3 = Color3.fromRGB(255, 255, 255)})
	--
	local tweenInfo6 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween6 = l__TweenService__14:Create(script.Parent.Parent.Misc, tweenInfo6, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	--
	local tweenInfo7 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween7 = l__TweenService__14:Create(script.Parent.Parent.Combat, tweenInfo7, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	--
	local tweenInfo7 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween7 = l__TweenService__14:Create(script.Parent.Parent.Combat, tweenInfo7, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	
	local awdastwelgwhwoaffjpfsdsad = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local asdawatrawe2411213w = l__TweenService__14:Create(script.Parent, awdastwelgwhwoaffjpfsdsad, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	--
	local tweenInfo31 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween31 = l__TweenService__14:Create(OtherFrame3, tweenInfo31, {Transparency = 1})
	
	local tweenInfo41 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween41 = l__TweenService__14:Create(OtherFrame4, tweenInfo41, {Transparency = 1})
	
	local tweenInfo41tweenInfo41tweenInfo41 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween41Tween41Tween41Tween41 = l__TweenService__14:Create(script.Parent.Parent.Credit.Line, tweenInfo41tweenInfo41tweenInfo41, {Transparency = 1})
	
	local tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween41Tween41Tween41Tween41Tween41Tween41Tween41Tween41 = l__TweenService__14:Create(script.Parent.Parent.Credit.Line2, tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41tweenInfo41, {Transparency = 1})
	
	local tweenInfo7tweenInfo7tweenInfo7tweenInfo7 = TweenInfo.new(
		0.9,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local tween7tween7tween7 = l__TweenService__14:Create(script.Parent.Parent.Credit, tweenInfo7tweenInfo7tweenInfo7tweenInfo7, {TextColor3 = Color3.fromRGB(61, 59, 61)})
	script.Parent.MouseButton1Click:Connect(function()
		if onoff == true  then
		Tween:Play()
		Tween2:Play()
		Tween3:Play()
		Tween4:Play()
		tween5:Play()
		tween6:Play()
		tween7:Play()
		Tween31:Play()
			Tween41:Play()
			tween7tween7tween7:Play()
			Tween41Tween41Tween41Tween41:Play()
			Tween41Tween41Tween41Tween41Tween41Tween41Tween41Tween41:Play()
			script.Parent.Parent.SettingsFrame.Visible = true
			script.Parent.Parent.CombatFrame.Visible = false
			script.Parent.Parent.CombatFrame.UI.ui.FrameEffect.Transparency = 1
			script.Parent.Parent.CombatFrame.UI.ui.FrameEffect2.Transparency = 1
			script.Parent.Parent.CombatFrame.UI.MainPage.Visible = false
			script.Parent.Parent.CreditFrame.Visible = false
			script.Parent.Parent.CreditFrame.UI.ui.FrameEffect.Transparency = 1
			script.Parent.Parent.CreditFrame.UI.ui.FrameEffect2.Transparency = 1
			script.Parent.Parent.CreditFrame.UI.MainPage.Visible = false
			onoff = false
		else
			wait(0.2)
			onoff = true
			yoama:Play()
			yoama2:Play()
			asdawatrawe2411213w:Play()
			script.Parent.Parent.SettingsFrame.Visible = false
		end
	end)
end;
task.spawn(C_1f);
-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.ui.LocalScript
local function C_33()
local script = G2L["33"];
	local Frame1 = script.Parent.FrameEffect
	local Frame2 = script.Parent.FrameEffect2
	local l__TweenService__14 = game:GetService("TweenService");
	
	local tweenInfo = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween = l__TweenService__14:Create(Frame1, tweenInfo, {Transparency = 0.8})
	
	local tweenInfo2 = TweenInfo.new(
		0.8,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween2 = l__TweenService__14:Create(Frame2, tweenInfo2, {Transparency = 0})
	--
	
	local tweenInfo3 = TweenInfo.new(
		0.5,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween3 = l__TweenService__14:Create(Frame1, tweenInfo3, {Transparency = 1})
	
	local tweenInfo4 = TweenInfo.new(
		0.5,
		Enum.EasingStyle.Quint,
		Enum.EasingDirection.Out, 
		0, 
		false,
		0
	)
	local Tween4 = l__TweenService__14:Create(Frame2, tweenInfo4, {Transparency = 1})
	--
	local onoff = true
	script.Parent.MouseButton1Click:Connect(function()
		if onoff == true then
		    Tween:Play()
			Tween2:Play()
			script.Parent.Parent.MainPage.Visible = true
			onoff = false
		else
			wait(0.2)
			onoff = true
			script.Parent.Parent.MainPage.Visible = false
			Tween3:Play()
			Tween4:Play()
		end
	end)
end;
task.spawn(C_33);
-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Blur.LocalScript
local function C_48()
local script = G2L["48"];
	local onoff = true
	local l__TweenService__14 = game:GetService("TweenService");
	local v44 = Instance.new("BlurEffect")
	v44.Parent = game.Lighting
	script.Parent.MouseButton1Click:Connect(function()
		if onoff == true then
			script.Parent.Frame.ToggleFrame.Circle:TweenPosition(UDim2.new(0.2,0,0.5,0),Enum.EasingDirection.InOut,Enum.EasingStyle.Linear,0.09)
			script.Parent.Frame.ToggleFrame.BackgroundColor3 = Color3.fromRGB(22, 21, 22)
			v44.Enabled = true
			l__TweenService__14:Create(v44, TweenInfo.new(1, Enum.EasingStyle.Quint), {
				Size = 0
			}):Play();
			onoff = false
		else
			wait(0.2)
			onoff = true
			script.Parent.Frame.ToggleFrame.BackgroundColor3 = Color3.fromRGB(52, 49, 52)
			script.Parent.Frame.ToggleFrame.Circle:TweenPosition(UDim2.new(0.8,0,0.5,0),Enum.EasingDirection.InOut,Enum.EasingStyle.Linear,0.09)
			l__TweenService__14:Create(v44, TweenInfo.new(1, Enum.EasingStyle.Quint), {
				Size = 25
			}):Play();
			wait(1)
		end
	end)
end;
task.spawn(C_48);
-- StarterGui.MainScreenGui.Frame.MainFrame.SettingsFrame.UI.MainPage.Color.LocalScript
local function C_5d()
local script = G2L["5d"];
	local onoff = true 
	local UIGrad = scrip
