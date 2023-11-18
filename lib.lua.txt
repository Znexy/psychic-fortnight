
-- Instances: 19 | Scripts: 0 | Modules: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;

-- StarterGui.ScreenGui.GUI
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(28, 28, 28);
G2L["2"]["Size"] = UDim2.new(0, 719, 0, 485);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Position"] = UDim2.new(0.23750855028629303, 0, 0.19129438698291779, 0);
G2L["2"]["Name"] = [[GUI]];

-- StarterGui.ScreenGui.GUI.Title
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["3"]["Size"] = UDim2.new(0, 718, 0, 78);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Position"] = UDim2.new(4.2444476378022955e-08, 0, 0, 0);
G2L["3"]["Name"] = [[Title]];

-- StarterGui.ScreenGui.GUI.Title.UICorner
G2L["4"] = Instance.new("UICorner", G2L["3"]);
G2L["4"]["CornerRadius"] = UDim.new(0, 3);

-- StarterGui.ScreenGui.GUI.Title.TitleText
G2L["5"] = Instance.new("TextLabel", G2L["3"]);
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5"]["TextSize"] = 30;
G2L["5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["Size"] = UDim2.new(0, 173, 0, 78);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Text"] = [[GUI Menu]];
G2L["5"]["Name"] = [[TitleText]];
G2L["5"]["BackgroundTransparency"] = 1;
G2L["5"]["Position"] = UDim2.new(-8.500717996184903e-08, 0, 0, 0);

-- StarterGui.ScreenGui.GUI.Title.closeBtn
G2L["6"] = Instance.new("ImageLabel", G2L["3"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["Image"] = [[http://www.roblox.com/asset/?id=6031094678]];
G2L["6"]["Size"] = UDim2.new(0, 30, 0, 30);
G2L["6"]["Name"] = [[closeBtn]];
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Position"] = UDim2.new(0, 679, 0, 24);

-- StarterGui.ScreenGui.GUI.UICorner
G2L["7"] = Instance.new("UICorner", G2L["2"]);


-- StarterGui.ScreenGui.Line
G2L["8"] = Instance.new("Frame", G2L["1"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(141, 141, 141);
G2L["8"]["Size"] = UDim2.new(0, 718, 0, -2);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Position"] = UDim2.new(0, 290, 0, 229);
G2L["8"]["Name"] = [[Line]];

-- StarterGui.ScreenGui.TabsHolder
G2L["9"] = Instance.new("Frame", G2L["1"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(37, 37, 37);
G2L["9"]["Size"] = UDim2.new(0, 187, 0, 406);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Position"] = UDim2.new(0.23800000548362732, 0, 0.289000004529953, 0);
G2L["9"]["Name"] = [[TabsHolder]];

-- StarterGui.ScreenGui.TabsHolder.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);


-- StarterGui.ScreenGui.TabsHolder.Tab
G2L["b"] = Instance.new("Frame", G2L["9"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["b"]["Size"] = UDim2.new(0, 187, 0, 30);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Position"] = UDim2.new(-0.0029277291614562273, 0, 0.0010000144829973578, 0);
G2L["b"]["Name"] = [[Tab]];

-- StarterGui.ScreenGui.TabsHolder.Tab.UICorner
G2L["c"] = Instance.new("UICorner", G2L["b"]);
G2L["c"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.ScreenGui.TabsHolder.Tab.TextButton
G2L["d"] = Instance.new("TextButton", G2L["b"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["d"]["TextSize"] = 20;
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Size"] = UDim2.new(0, 187, 0, 30);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[gfh]];
G2L["d"]["Position"] = UDim2.new(0, 0, -0.03333333507180214, 0);

-- StarterGui.ScreenGui.TabsHolder.Tab.TextButton.UICorner
G2L["e"] = Instance.new("UICorner", G2L["d"]);


-- StarterGui.ScreenGui.TabsHolder.Frame
G2L["f"] = Instance.new("Frame", G2L["9"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Size"] = UDim2.new(0, 186, 0, 8);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Position"] = UDim2.new(0, 0, 0.07389162480831146, 0);

-- StarterGui.ScreenGui.TabsHolder.Tab
G2L["10"] = Instance.new("Frame", G2L["9"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["10"]["Size"] = UDim2.new(0, 187, 0, 30);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Position"] = UDim2.new(-0.0029277291614562273, 0, 0.0010000144829973578, 0);
G2L["10"]["Name"] = [[Tab]];

-- StarterGui.ScreenGui.TabsHolder.Tab.UICorner
G2L["11"] = Instance.new("UICorner", G2L["10"]);
G2L["11"]["CornerRadius"] = UDim.new(0, 4);

-- StarterGui.ScreenGui.TabsHolder.Tab.TextButton
G2L["12"] = Instance.new("TextButton", G2L["10"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["12"]["TextSize"] = 20;
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["Size"] = UDim2.new(0, 187, 0, 30);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Position"] = UDim2.new(0, 0, 1.4666666984558105, 0);

-- StarterGui.ScreenGui.TabsHolder.Tab.TextButton.UICorner
G2L["13"] = Instance.new("UICorner", G2L["12"]);



return G2L["1"], require;
