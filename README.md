 while wait() do
           for fd, fe in pairs(game:GetService("Workspace").Camera:GetChildren()) do
             fe:Destroy()
           end
     end
    if game:GetService("Players").LocalPlayer.PlayerGui.Dmg then
       game:GetService("Players").LocalPlayer.PlayerGui.Dmg:Destroy()
       end
