
--Converted with ttyyuu12345's model to script plugin v4
function sandbox(var,func)
	local env = getfenv(func)
	local newenv = setmetatable({},{
		__index = function(self,k)
			if k=="script" then
				return var
			else
				return env[k]
			end
		end,
	})
	setfenv(func,newenv)
	return func
end
cors = {}
mas = Instance.new("Model",game:GetService("Lighting"))
ScreenGui0 = Instance.new("ScreenGui")
Frame1 = Instance.new("Frame")
TextLabel2 = Instance.new("TextLabel")
LocalScript3 = Instance.new("LocalScript")
TextLabel4 = Instance.new("TextLabel")
UIListLayout5 = Instance.new("UIListLayout")
TextLabel6 = Instance.new("TextLabel")
LocalScript7 = Instance.new("LocalScript")
TextLabel8 = Instance.new("TextLabel")
TextLabel9 = Instance.new("TextLabel")
LocalScript10 = Instance.new("LocalScript")
TextLabel11 = Instance.new("TextLabel")
TextLabel12 = Instance.new("TextLabel")
TextLabel13 = Instance.new("TextLabel")
TextLabel14 = Instance.new("TextLabel")
LocalScript15 = Instance.new("LocalScript")
TextLabel16 = Instance.new("TextLabel")
Frame17 = Instance.new("Frame")
Frame18 = Instance.new("Frame")
Frame19 = Instance.new("Frame")
LocalScript20 = Instance.new("LocalScript")
ImageButton21 = Instance.new("ImageButton")
Frame22 = Instance.new("Frame")
Frame23 = Instance.new("Frame")
Frame24 = Instance.new("Frame")
Frame25 = Instance.new("Frame")
TextButton26 = Instance.new("TextButton")
Frame27 = Instance.new("Frame")
TextButton28 = Instance.new("TextButton")
TextButton29 = Instance.new("TextButton")
TextButton30 = Instance.new("TextButton")
TextButton31 = Instance.new("TextButton")
TextButton32 = Instance.new("TextButton")
LocalScript33 = Instance.new("LocalScript")
ImageButton34 = Instance.new("ImageButton")
TextLabel35 = Instance.new("TextLabel")
LocalScript36 = Instance.new("LocalScript")
ImageButton37 = Instance.new("ImageButton")
TextLabel38 = Instance.new("TextLabel")
LocalScript39 = Instance.new("LocalScript")
ImageButton40 = Instance.new("ImageButton")
TextLabel41 = Instance.new("TextLabel")
LocalScript42 = Instance.new("LocalScript")
ImageButton43 = Instance.new("ImageButton")
LocalScript44 = Instance.new("LocalScript")
TextLabel45 = Instance.new("TextLabel")
ImageButton46 = Instance.new("ImageButton")
LocalScript47 = Instance.new("LocalScript")
TextLabel48 = Instance.new("TextLabel")
TextLabel49 = Instance.new("TextLabel")
Frame50 = Instance.new("Frame")
ImageButton51 = Instance.new("ImageButton")
TextLabel52 = Instance.new("TextLabel")
LocalScript53 = Instance.new("LocalScript")
BoolValue54 = Instance.new("BoolValue")
TextLabel55 = Instance.new("TextLabel")
Frame56 = Instance.new("Frame")
Frame57 = Instance.new("Frame")
TextButton58 = Instance.new("TextButton")
LocalScript59 = Instance.new("LocalScript")
TextLabel60 = Instance.new("TextLabel")
NumberValue61 = Instance.new("NumberValue")
ImageButton62 = Instance.new("ImageButton")
TextLabel63 = Instance.new("TextLabel")
ImageButton64 = Instance.new("ImageButton")
TextLabel65 = Instance.new("TextLabel")
Frame66 = Instance.new("Frame")
TextButton67 = Instance.new("TextButton")
Frame68 = Instance.new("Frame")
TextButton69 = Instance.new("TextButton")
TextButton70 = Instance.new("TextButton")
LocalScript71 = Instance.new("LocalScript")
ImageButton72 = Instance.new("ImageButton")
TextLabel73 = Instance.new("TextLabel")
LocalScript74 = Instance.new("LocalScript")
ImageButton75 = Instance.new("ImageButton")
TextLabel76 = Instance.new("TextLabel")
Frame77 = Instance.new("Frame")
Frame78 = Instance.new("Frame")
TextButton79 = Instance.new("TextButton")
LocalScript80 = Instance.new("LocalScript")
TextLabel81 = Instance.new("TextLabel")
NumberValue82 = Instance.new("NumberValue")
Frame83 = Instance.new("Frame")
LocalScript84 = Instance.new("LocalScript")
Frame85 = Instance.new("Frame")
Frame86 = Instance.new("Frame")
ImageButton87 = Instance.new("ImageButton")
LocalScript88 = Instance.new("LocalScript")
TextLabel89 = Instance.new("TextLabel")
ImageButton90 = Instance.new("ImageButton")
TextLabel91 = Instance.new("TextLabel")
ImageButton92 = Instance.new("ImageButton")
LocalScript93 = Instance.new("LocalScript")
TextLabel94 = Instance.new("TextLabel")
ImageButton95 = Instance.new("ImageButton")
ImageButton96 = Instance.new("ImageButton")
TextLabel97 = Instance.new("TextLabel")
LocalScript98 = Instance.new("LocalScript")
ImageButton99 = Instance.new("ImageButton")
ImageButton100 = Instance.new("ImageButton")
Frame101 = Instance.new("Frame")
TextButton102 = Instance.new("TextButton")
Frame103 = Instance.new("Frame")
TextButton104 = Instance.new("TextButton")
TextButton105 = Instance.new("TextButton")
TextButton106 = Instance.new("TextButton")
LocalScript107 = Instance.new("LocalScript")
ImageButton108 = Instance.new("ImageButton")
TextLabel109 = Instance.new("TextLabel")
LocalScript110 = Instance.new("LocalScript")
ImageButton111 = Instance.new("ImageButton")
Frame112 = Instance.new("Frame")
TextButton113 = Instance.new("TextButton")
Frame114 = Instance.new("Frame")
TextButton115 = Instance.new("TextButton")
TextButton116 = Instance.new("TextButton")
TextButton117 = Instance.new("TextButton")
LocalScript118 = Instance.new("LocalScript")
Frame119 = Instance.new("Frame")
Frame120 = Instance.new("Frame")
TextButton121 = Instance.new("TextButton")
Frame122 = Instance.new("Frame")
TextButton123 = Instance.new("TextButton")
TextButton124 = Instance.new("TextButton")
TextButton125 = Instance.new("TextButton")
TextButton126 = Instance.new("TextButton")
TextButton127 = Instance.new("TextButton")
TextButton128 = Instance.new("TextButton")
LocalScript129 = Instance.new("LocalScript")
ImageButton130 = Instance.new("ImageButton")
TextLabel131 = Instance.new("TextLabel")
LocalScript132 = Instance.new("LocalScript")
ImageButton133 = Instance.new("ImageButton")
ImageButton134 = Instance.new("ImageButton")
TextLabel135 = Instance.new("TextLabel")
LocalScript136 = Instance.new("LocalScript")
ImageButton137 = Instance.new("ImageButton")
LocalScript138 = Instance.new("LocalScript")
TextBox139 = Instance.new("TextBox")
TextLabel140 = Instance.new("TextLabel")
TextLabel141 = Instance.new("TextLabel")
ImageButton142 = Instance.new("ImageButton")
TextLabel143 = Instance.new("TextLabel")
LocalScript144 = Instance.new("LocalScript")
ImageButton145 = Instance.new("ImageButton")
TextLabel146 = Instance.new("TextLabel")
LocalScript147 = Instance.new("LocalScript")
ImageButton148 = Instance.new("ImageButton")
TextLabel149 = Instance.new("TextLabel")
LocalScript150 = Instance.new("LocalScript")
ImageButton151 = Instance.new("ImageButton")
TextLabel152 = Instance.new("TextLabel")
LocalScript153 = Instance.new("LocalScript")
ImageButton154 = Instance.new("ImageButton")
TextLabel155 = Instance.new("TextLabel")
LocalScript156 = Instance.new("LocalScript")
ImageButton157 = Instance.new("ImageButton")
TextLabel158 = Instance.new("TextLabel")
LocalScript159 = Instance.new("LocalScript")
Frame160 = Instance.new("Frame")
TextButton161 = Instance.new("TextButton")
Frame162 = Instance.new("Frame")
TextButton163 = Instance.new("TextButton")
TextButton164 = Instance.new("TextButton")
TextButton165 = Instance.new("TextButton")
LocalScript166 = Instance.new("LocalScript")
ImageButton167 = Instance.new("ImageButton")
TextLabel168 = Instance.new("TextLabel")
LocalScript169 = Instance.new("LocalScript")
Frame170 = Instance.new("Frame")
ImageButton171 = Instance.new("ImageButton")
LocalScript172 = Instance.new("LocalScript")
TextLabel173 = Instance.new("TextLabel")
ImageButton174 = Instance.new("ImageButton")
ImageButton175 = Instance.new("ImageButton")
TextLabel176 = Instance.new("TextLabel")
ImageButton177 = Instance.new("ImageButton")
ImageButton178 = Instance.new("ImageButton")
TextLabel179 = Instance.new("TextLabel")
ImageButton180 = Instance.new("ImageButton")
ImageButton181 = Instance.new("ImageButton")
TextLabel182 = Instance.new("TextLabel")
ImageButton183 = Instance.new("ImageButton")
LocalScript184 = Instance.new("LocalScript")
TextLabel185 = Instance.new("TextLabel")
ImageButton186 = Instance.new("ImageButton")
TextLabel187 = Instance.new("TextLabel")
ImageButton188 = Instance.new("ImageButton")
ImageButton189 = Instance.new("ImageButton")
TextLabel190 = Instance.new("TextLabel")
ImageButton191 = Instance.new("ImageButton")
TextLabel192 = Instance.new("TextLabel")
ImageButton193 = Instance.new("ImageButton")
TextLabel194 = Instance.new("TextLabel")
TextLabel195 = Instance.new("TextLabel")
Frame196 = Instance.new("Frame")
ImageButton197 = Instance.new("ImageButton")
LocalScript198 = Instance.new("LocalScript")
TextLabel199 = Instance.new("TextLabel")
ImageButton200 = Instance.new("ImageButton")
LocalScript201 = Instance.new("LocalScript")
TextLabel202 = Instance.new("TextLabel")
ImageButton203 = Instance.new("ImageButton")
LocalScript204 = Instance.new("LocalScript")
TextLabel205 = Instance.new("TextLabel")
ImageButton206 = Instance.new("ImageButton")
ImageButton207 = Instance.new("ImageButton")
LocalScript208 = Instance.new("LocalScript")
TextLabel209 = Instance.new("TextLabel")
ImageButton210 = Instance.new("ImageButton")
ImageButton211 = Instance.new("ImageButton")
LocalScript212 = Instance.new("LocalScript")
TextLabel213 = Instance.new("TextLabel")
ImageButton214 = Instance.new("ImageButton")
ImageButton215 = Instance.new("ImageButton")
LocalScript216 = Instance.new("LocalScript")
TextLabel217 = Instance.new("TextLabel")
ImageButton218 = Instance.new("ImageButton")
ImageButton219 = Instance.new("ImageButton")
TextLabel220 = Instance.new("TextLabel")
LocalScript221 = Instance.new("LocalScript")
ImageButton222 = Instance.new("ImageButton")
LocalScript223 = Instance.new("LocalScript")
TextLabel224 = Instance.new("TextLabel")
ImageButton225 = Instance.new("ImageButton")
ImageButton226 = Instance.new("ImageButton")
LocalScript227 = Instance.new("LocalScript")
TextLabel228 = Instance.new("TextLabel")
ImageButton229 = Instance.new("ImageButton")
ImageButton230 = Instance.new("ImageButton")
TextLabel231 = Instance.new("TextLabel")
LocalScript232 = Instance.new("LocalScript")
ImageButton233 = Instance.new("ImageButton")
TextLabel234 = Instance.new("TextLabel")
ImageButton235 = Instance.new("ImageButton")
ImageButton236 = Instance.new("ImageButton")
LocalScript237 = Instance.new("LocalScript")
TextLabel238 = Instance.new("TextLabel")
ImageButton239 = Instance.new("ImageButton")
Frame240 = Instance.new("Frame")
Frame241 = Instance.new("Frame")
Frame242 = Instance.new("Frame")
LocalScript243 = Instance.new("LocalScript")
Frame244 = Instance.new("Frame")
Frame245 = Instance.new("Frame")
TextLabel246 = Instance.new("TextLabel")
Frame247 = Instance.new("Frame")
TextButton248 = Instance.new("TextButton")
LocalScript249 = Instance.new("LocalScript")
LocalScript250 = Instance.new("LocalScript")
TextButton251 = Instance.new("TextButton")
LocalScript252 = Instance.new("LocalScript")
TextButton253 = Instance.new("TextButton")
LocalScript254 = Instance.new("LocalScript")
TextButton255 = Instance.new("TextButton")
LocalScript256 = Instance.new("LocalScript")
TextButton257 = Instance.new("TextButton")
LocalScript258 = Instance.new("LocalScript")
TextButton259 = Instance.new("TextButton")
LocalScript260 = Instance.new("LocalScript")
TextButton261 = Instance.new("TextButton")
LocalScript262 = Instance.new("LocalScript")
TextButton263 = Instance.new("TextButton")
LocalScript264 = Instance.new("LocalScript")
TextButton265 = Instance.new("TextButton")
LocalScript266 = Instance.new("LocalScript")
TextButton267 = Instance.new("TextButton")
LocalScript268 = Instance.new("LocalScript")
TextButton269 = Instance.new("TextButton")
LocalScript270 = Instance.new("LocalScript")
TextButton271 = Instance.new("TextButton")
LocalScript272 = Instance.new("LocalScript")
TextButton273 = Instance.new("TextButton")
LocalScript274 = Instance.new("LocalScript")
TextButton275 = Instance.new("TextButton")
LocalScript276 = Instance.new("LocalScript")
Frame277 = Instance.new("Frame")
TextLabel278 = Instance.new("TextLabel")
TextLabel279 = Instance.new("TextLabel")
TextLabel280 = Instance.new("TextLabel")
TextLabel281 = Instance.new("TextLabel")
TextLabel282 = Instance.new("TextLabel")
TextLabel283 = Instance.new("TextLabel")
TextLabel284 = Instance.new("TextLabel")
TextLabel285 = Instance.new("TextLabel")
TextLabel286 = Instance.new("TextLabel")
TextLabel287 = Instance.new("TextLabel")
ImageButton288 = Instance.new("ImageButton")
ImageButton289 = Instance.new("ImageButton")
Frame290 = Instance.new("Frame")
Frame291 = Instance.new("Frame")
Frame292 = Instance.new("Frame")
LocalScript293 = Instance.new("LocalScript")
ImageButton294 = Instance.new("ImageButton")
Frame295 = Instance.new("Frame")
Frame296 = Instance.new("Frame")
Frame297 = Instance.new("Frame")
Frame298 = Instance.new("Frame")
TextLabel299 = Instance.new("TextLabel")
Frame300 = Instance.new("Frame")
TextLabel301 = Instance.new("TextLabel")
Frame302 = Instance.new("Frame")
TextLabel303 = Instance.new("TextLabel")
Frame304 = Instance.new("Frame")
LocalScript305 = Instance.new("LocalScript")
Frame306 = Instance.new("Frame")
Frame307 = Instance.new("Frame")
TextLabel308 = Instance.new("TextLabel")
Frame309 = Instance.new("Frame")
Frame310 = Instance.new("Frame")
TextButton311 = Instance.new("TextButton")
Frame312 = Instance.new("Frame")
TextButton313 = Instance.new("TextButton")
TextButton314 = Instance.new("TextButton")
TextButton315 = Instance.new("TextButton")
TextButton316 = Instance.new("TextButton")
TextButton317 = Instance.new("TextButton")
TextButton318 = Instance.new("TextButton")
LocalScript319 = Instance.new("LocalScript")
ImageButton320 = Instance.new("ImageButton")
TextLabel321 = Instance.new("TextLabel")
LocalScript322 = Instance.new("LocalScript")
TextLabel323 = Instance.new("TextLabel")
Frame324 = Instance.new("Frame")
TextLabel325 = Instance.new("TextLabel")
ImageButton326 = Instance.new("ImageButton")
TextLabel327 = Instance.new("TextLabel")
LocalScript328 = Instance.new("LocalScript")
ImageButton329 = Instance.new("ImageButton")
TextLabel330 = Instance.new("TextLabel")
LocalScript331 = Instance.new("LocalScript")
ImageButton332 = Instance.new("ImageButton")
TextLabel333 = Instance.new("TextLabel")
LocalScript334 = Instance.new("LocalScript")
ImageButton335 = Instance.new("ImageButton")
TextLabel336 = Instance.new("TextLabel")
LocalScript337 = Instance.new("LocalScript")
ImageButton338 = Instance.new("ImageButton")
TextLabel339 = Instance.new("TextLabel")
LocalScript340 = Instance.new("LocalScript")
ImageButton341 = Instance.new("ImageButton")
LocalScript342 = Instance.new("LocalScript")
TextLabel343 = Instance.new("TextLabel")
ImageButton344 = Instance.new("ImageButton")
TextLabel345 = Instance.new("TextLabel")
LocalScript346 = Instance.new("LocalScript")
ImageButton347 = Instance.new("ImageButton")
TextLabel348 = Instance.new("TextLabel")
LocalScript349 = Instance.new("LocalScript")
ImageButton350 = Instance.new("ImageButton")
TextLabel351 = Instance.new("TextLabel")
LocalScript352 = Instance.new("LocalScript")
ImageButton353 = Instance.new("ImageButton")
TextLabel354 = Instance.new("TextLabel")
LocalScript355 = Instance.new("LocalScript")
ImageButton356 = Instance.new("ImageButton")
TextLabel357 = Instance.new("TextLabel")
LocalScript358 = Instance.new("LocalScript")
ImageButton359 = Instance.new("ImageButton")
TextLabel360 = Instance.new("TextLabel")
LocalScript361 = Instance.new("LocalScript")
ImageButton362 = Instance.new("ImageButton")
TextLabel363 = Instance.new("TextLabel")
LocalScript364 = Instance.new("LocalScript")
ImageButton365 = Instance.new("ImageButton")
TextLabel366 = Instance.new("TextLabel")
LocalScript367 = Instance.new("LocalScript")
ImageButton368 = Instance.new("ImageButton")
TextLabel369 = Instance.new("TextLabel")
LocalScript370 = Instance.new("LocalScript")
Frame371 = Instance.new("Frame")
Frame372 = Instance.new("Frame")
TextButton373 = Instance.new("TextButton")
LocalScript374 = Instance.new("LocalScript")
TextLabel375 = Instance.new("TextLabel")
NumberValue376 = Instance.new("NumberValue")
ImageButton377 = Instance.new("ImageButton")
Frame378 = Instance.new("Frame")
Frame379 = Instance.new("Frame")
Frame380 = Instance.new("Frame")
LocalScript381 = Instance.new("LocalScript")
ImageButton382 = Instance.new("ImageButton")
Frame383 = Instance.new("Frame")
Frame384 = Instance.new("Frame")
Frame385 = Instance.new("Frame")
Frame386 = Instance.new("Frame")
ImageButton387 = Instance.new("ImageButton")
LocalScript388 = Instance.new("LocalScript")
LocalScript389 = Instance.new("LocalScript")
TextLabel390 = Instance.new("TextLabel")
TextLabel391 = Instance.new("TextLabel")
ImageButton392 = Instance.new("ImageButton")
TextLabel393 = Instance.new("TextLabel")
Frame394 = Instance.new("Frame")
TextButton395 = Instance.new("TextButton")
Frame396 = Instance.new("Frame")
TextButton397 = Instance.new("TextButton")
TextButton398 = Instance.new("TextButton")
TextButton399 = Instance.new("TextButton")
LocalScript400 = Instance.new("LocalScript")
Frame401 = Instance.new("Frame")
Frame402 = Instance.new("Frame")
TextButton403 = Instance.new("TextButton")
LocalScript404 = Instance.new("LocalScript")
TextLabel405 = Instance.new("TextLabel")
NumberValue406 = Instance.new("NumberValue")
ImageButton407 = Instance.new("ImageButton")
TextLabel408 = Instance.new("TextLabel")
Frame409 = Instance.new("Frame")
Frame410 = Instance.new("Frame")
TextButton411 = Instance.new("TextButton")
Frame412 = Instance.new("Frame")
TextButton413 = Instance.new("TextButton")
TextButton414 = Instance.new("TextButton")
TextButton415 = Instance.new("TextButton")
TextButton416 = Instance.new("TextButton")
TextButton417 = Instance.new("TextButton")
TextButton418 = Instance.new("TextButton")
TextButton419 = Instance.new("TextButton")
LocalScript420 = Instance.new("LocalScript")
ImageButton421 = Instance.new("ImageButton")
TextLabel422 = Instance.new("TextLabel")
ImageButton423 = Instance.new("ImageButton")
TextLabel424 = Instance.new("TextLabel")
ImageButton425 = Instance.new("ImageButton")
LocalScript426 = Instance.new("LocalScript")
LocalScript427 = Instance.new("LocalScript")
TextLabel428 = Instance.new("TextLabel")
LocalScript429 = Instance.new("LocalScript")
Frame430 = Instance.new("Frame")
TextButton431 = Instance.new("TextButton")
Frame432 = Instance.new("Frame")
TextButton433 = Instance.new("TextButton")
TextButton434 = Instance.new("TextButton")
TextButton435 = Instance.new("TextButton")
LocalScript436 = Instance.new("LocalScript")
TextLabel437 = Instance.new("TextLabel")
Frame438 = Instance.new("Frame")
ImageButton439 = Instance.new("ImageButton")
TextLabel440 = Instance.new("TextLabel")
LocalScript441 = Instance.new("LocalScript")
ImageButton442 = Instance.new("ImageButton")
TextLabel443 = Instance.new("TextLabel")
LocalScript444 = Instance.new("LocalScript")
ImageButton445 = Instance.new("ImageButton")
TextLabel446 = Instance.new("TextLabel")
LocalScript447 = Instance.new("LocalScript")
TextLabel448 = Instance.new("TextLabel")
ImageButton449 = Instance.new("ImageButton")
TextLabel450 = Instance.new("TextLabel")
LocalScript451 = Instance.new("LocalScript")
Frame452 = Instance.new("Frame")
LocalScript453 = Instance.new("LocalScript")
ImageButton454 = Instance.new("ImageButton")
Frame455 = Instance.new("Frame")
Frame456 = Instance.new("Frame")
Frame457 = Instance.new("Frame")
Frame458 = Instance.new("Frame")
Frame459 = Instance.new("Frame")
TextLabel460 = Instance.new("TextLabel")
Frame461 = Instance.new("Frame")
TextLabel462 = Instance.new("TextLabel")
Frame463 = Instance.new("Frame")
TextLabel464 = Instance.new("TextLabel")
Frame465 = Instance.new("Frame")
Frame466 = Instance.new("Frame")
TextLabel467 = Instance.new("TextLabel")
Frame468 = Instance.new("Frame")
TextLabel469 = Instance.new("TextLabel")
Frame470 = Instance.new("Frame")
TextLabel471 = Instance.new("TextLabel")
Frame472 = Instance.new("Frame")
Frame473 = Instance.new("Frame")
TextLabel474 = Instance.new("TextLabel")
Frame475 = Instance.new("Frame")
TextLabel476 = Instance.new("TextLabel")
Frame477 = Instance.new("Frame")
TextLabel478 = Instance.new("TextLabel")
Frame479 = Instance.new("Frame")
Frame480 = Instance.new("Frame")
TextLabel481 = Instance.new("TextLabel")
Frame482 = Instance.new("Frame")
TextLabel483 = Instance.new("TextLabel")
Frame484 = Instance.new("Frame")
TextLabel485 = Instance.new("TextLabel")
Frame486 = Instance.new("Frame")
Frame487 = Instance.new("Frame")
TextLabel488 = Instance.new("TextLabel")
Frame489 = Instance.new("Frame")
TextLabel490 = Instance.new("TextLabel")
Frame491 = Instance.new("Frame")
TextLabel492 = Instance.new("TextLabel")
Frame493 = Instance.new("Frame")
ImageButton494 = Instance.new("ImageButton")
LocalScript495 = Instance.new("LocalScript")
ImageButton496 = Instance.new("ImageButton")
LocalScript497 = Instance.new("LocalScript")
ImageButton498 = Instance.new("ImageButton")
LocalScript499 = Instance.new("LocalScript")
ImageButton500 = Instance.new("ImageButton")
LocalScript501 = Instance.new("LocalScript")
ImageButton502 = Instance.new("ImageButton")
LocalScript503 = Instance.new("LocalScript")
ImageButton504 = Instance.new("ImageButton")
LocalScript505 = Instance.new("LocalScript")
Frame506 = Instance.new("Frame")
Frame507 = Instance.new("Frame")
TextLabel508 = Instance.new("TextLabel")
Frame509 = Instance.new("Frame")
TextLabel510 = Instance.new("TextLabel")
Frame511 = Instance.new("Frame")
TextLabel512 = Instance.new("TextLabel")
Frame513 = Instance.new("Frame")
LocalScript514 = Instance.new("LocalScript")
LocalScript515 = Instance.new("LocalScript")
UIScale516 = Instance.new("UIScale")
LocalScript517 = Instance.new("LocalScript")
LocalScript518 = Instance.new("LocalScript")
Frame519 = Instance.new("Frame")
TextLabel520 = Instance.new("TextLabel")
LocalScript521 = Instance.new("LocalScript")
LocalScript522 = Instance.new("LocalScript")
LocalScript523 = Instance.new("LocalScript")
TextLabel524 = Instance.new("TextLabel")
TextLabel525 = Instance.new("TextLabel")
TextLabel526 = Instance.new("TextLabel")
TextLabel527 = Instance.new("TextLabel")
TextLabel528 = Instance.new("TextLabel")
TextLabel529 = Instance.new("TextLabel")
TextLabel530 = Instance.new("TextLabel")
ScreenGui0.Name = "gamesense.pub"
ScreenGui0.Parent = mas
ScreenGui0.DisplayOrder = 99999999
Frame1.Name = "tags"
Frame1.Parent = ScreenGui0
Frame1.Position = UDim2.new(0, 0, 0.811813712, 0)
Frame1.Visible = false
Frame1.Size = UDim2.new(0, 411, 0, 270)
Frame1.BackgroundColor = BrickColor.new("Really black")
Frame1.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
Frame1.BackgroundTransparency = 1
Frame1.BorderColor = BrickColor.new("Dirt brown")
Frame1.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame1.BorderSizePixel = 0
Frame1.SizeConstraint = Enum.SizeConstraint.RelativeXX
TextLabel2.Name = "FPSWARN"
TextLabel2.Parent = Frame1
TextLabel2.Visible = false
TextLabel2.Size = UDim2.new(0, 200, 0, 42)
TextLabel2.BackgroundColor = BrickColor.new("Institutional white")
TextLabel2.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel2.BackgroundTransparency = 1
TextLabel2.ZIndex = 2
TextLabel2.Font = Enum.Font.SourceSansBold
TextLabel2.FontSize = Enum.FontSize.Size48
TextLabel2.Text = "FPS"
TextLabel2.TextColor = BrickColor.new("Br. yellowish green")
TextLabel2.TextColor3 = Color3.new(0.647059, 1, 0.360784)
TextLabel2.TextSize = 46
TextLabel2.TextXAlignment = Enum.TextXAlignment.Left
LocalScript3.Parent = TextLabel2
table.insert(cors,sandbox(LocalScript3,function()
local fps = 0
local rs = game:GetService'RunService'

function updateFPS()
	fps = fps + 1
end

rs.RenderStepped:connect(updateFPS)

while wait(1) do
	if fps > 57 then
		script.Parent.Visible = false
	end
	if fps < 57 then
		script.Parent.TextColor3 = Color3.fromRGB(165, 255, 92)
		script.Parent.Visible = true
	end
	if fps < 45 then
		script.Parent.TextColor3 = Color3.fromRGB(246, 255, 66)
		script.Parent.Visible = true
	end
	if fps < 35 then
		script.Parent.TextColor3 = Color3.fromRGB(255, 63, 25)
		script.Parent.Visible = true
	end
	fps = 0
end
end))
TextLabel4.Parent = TextLabel2
TextLabel4.Position = UDim2.new(0, 1, 0, 1)
TextLabel4.Size = UDim2.new(0, 200, 0, 42)
TextLabel4.BackgroundColor = BrickColor.new("Institutional white")
TextLabel4.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel4.BackgroundTransparency = 1
TextLabel4.Font = Enum.Font.SourceSansBold
TextLabel4.FontSize = Enum.FontSize.Size48
TextLabel4.Text = "FPS"
TextLabel4.TextColor = BrickColor.new("Really black")
TextLabel4.TextColor3 = Color3.new(0, 0, 0)
TextLabel4.TextSize = 46
TextLabel4.TextXAlignment = Enum.TextXAlignment.Left
UIListLayout5.Parent = Frame1
UIListLayout5.SortOrder = Enum.SortOrder.LayoutOrder
TextLabel6.Name = "Anti aimbot"
TextLabel6.Parent = Frame1
TextLabel6.Visible = false
TextLabel6.Size = UDim2.new(0, 200, 0, 42)
TextLabel6.BackgroundColor = BrickColor.new("Institutional white")
TextLabel6.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel6.BackgroundTransparency = 1
TextLabel6.ZIndex = 2
TextLabel6.Font = Enum.Font.SourceSansBold
TextLabel6.FontSize = Enum.FontSize.Size48
TextLabel6.Text = "Anti aimbot"
TextLabel6.TextColor = BrickColor.new("Br. yellowish green")
TextLabel6.TextColor3 = Color3.new(0.647059, 1, 0.360784)
TextLabel6.TextSize = 46
TextLabel6.TextXAlignment = Enum.TextXAlignment.Left
LocalScript7.Parent = TextLabel6
table.insert(cors,sandbox(LocalScript7,function()
while wait() do
	if script.Parent.Parent.Parent.Main.Tabs.AA.Main.AntiAimTab.AA.BackgroundColor3 == Color3.fromRGB(181, 255, 42)
	then script.Parent.Visible = true
	end
	if script.Parent.Parent.Parent.Main.Tabs.AA.Main.AntiAimTab.AA.BackgroundColor3 ~= Color3.fromRGB(181, 255, 42)
	then script.Parent.Visible = false
	end
end

end))
TextLabel8.Parent = TextLabel6
TextLabel8.Position = UDim2.new(0, 1, 0, 1)
TextLabel8.Size = UDim2.new(0, 200, 0, 42)
TextLabel8.BackgroundColor = BrickColor.new("Institutional white")
TextLabel8.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel8.BackgroundTransparency = 1
TextLabel8.Font = Enum.Font.SourceSansBold
TextLabel8.FontSize = Enum.FontSize.Size48
TextLabel8.Text = "Anti aimbot"
TextLabel8.TextColor = BrickColor.new("Really black")
TextLabel8.TextColor3 = Color3.new(0, 0, 0)
TextLabel8.TextSize = 46
TextLabel8.TextXAlignment = Enum.TextXAlignment.Left
TextLabel9.Name = "Hitpart"
TextLabel9.Parent = Frame1
TextLabel9.Visible = false
TextLabel9.Size = UDim2.new(0, 200, 0, 42)
TextLabel9.BackgroundColor = BrickColor.new("Institutional white")
TextLabel9.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel9.BackgroundTransparency = 1
TextLabel9.ZIndex = 2
TextLabel9.Font = Enum.Font.SourceSansBold
TextLabel9.FontSize = Enum.FontSize.Size48
TextLabel9.Text = "Hitpart"
TextLabel9.TextColor = BrickColor.new("Br. yellowish green")
TextLabel9.TextColor3 = Color3.new(0.647059, 1, 0.360784)
TextLabel9.TextSize = 46
TextLabel9.TextXAlignment = Enum.TextXAlignment.Left
LocalScript10.Parent = TextLabel9
table.insert(cors,sandbox(LocalScript10,function()
while wait() do
	if script.Parent.Parent.Parent.Main.Tabs.Aim.Main.RageTab.Hitpart.BackgroundColor3 == Color3.fromRGB(181, 255, 42)
		then script.Parent.Visible = true
	end
	if script.Parent.Parent.Parent.Main.Tabs.Aim.Main.RageTab.Hitpart.BackgroundColor3 ~= Color3.fromRGB(181, 255, 42)
		then script.Parent.Visible = false
	end
end

end))
TextLabel11.Name = "Hitpart"
TextLabel11.Parent = TextLabel9
TextLabel11.Position = UDim2.new(0, 1, 0, 1)
TextLabel11.Size = UDim2.new(0, 200, 0, 42)
TextLabel11.BackgroundColor = BrickColor.new("Institutional white")
TextLabel11.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel11.BackgroundTransparency = 1
TextLabel11.Font = Enum.Font.SourceSansBold
TextLabel11.FontSize = Enum.FontSize.Size48
TextLabel11.Text = "Hitpart"
TextLabel11.TextColor = BrickColor.new("Really black")
TextLabel11.TextColor3 = Color3.new(0, 0, 0)
TextLabel11.TextSize = 46
TextLabel11.TextXAlignment = Enum.TextXAlignment.Left
TextLabel12.Name = "Fakelag"
TextLabel12.Parent = Frame1
TextLabel12.Visible = false
TextLabel12.Size = UDim2.new(0, 200, 0, 42)
TextLabel12.BackgroundColor = BrickColor.new("Institutional white")
TextLabel12.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel12.BackgroundTransparency = 1
TextLabel12.ZIndex = 2
TextLabel12.Font = Enum.Font.SourceSansBold
TextLabel12.FontSize = Enum.FontSize.Size48
TextLabel12.Text = "Fake"
TextLabel12.TextColor = BrickColor.new("Br. yellowish green")
TextLabel12.TextColor3 = Color3.new(0.647059, 1, 0.360784)
TextLabel12.TextSize = 46
TextLabel12.TextXAlignment = Enum.TextXAlignment.Left
TextLabel13.Name = "Hitpart"
TextLabel13.Parent = TextLabel12
TextLabel13.Position = UDim2.new(0, 1, 0, 1)
TextLabel13.Size = UDim2.new(0, 200, 0, 42)
TextLabel13.BackgroundColor = BrickColor.new("Institutional white")
TextLabel13.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel13.BackgroundTransparency = 1
TextLabel13.Font = Enum.Font.SourceSansBold
TextLabel13.FontSize = Enum.FontSize.Size48
TextLabel13.Text = "Fake"
TextLabel13.TextColor = BrickColor.new("Really black")
TextLabel13.TextColor3 = Color3.new(0, 0, 0)
TextLabel13.TextSize = 46
TextLabel13.TextXAlignment = Enum.TextXAlignment.Left
TextLabel14.Name = "Rage"
TextLabel14.Parent = Frame1
TextLabel14.Visible = false
TextLabel14.Size = UDim2.new(0, 200, 0, 42)
TextLabel14.BackgroundColor = BrickColor.new("Institutional white")
TextLabel14.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel14.BackgroundTransparency = 1
TextLabel14.ZIndex = 2
TextLabel14.Font = Enum.Font.SourceSansBold
TextLabel14.FontSize = Enum.FontSize.Size48
TextLabel14.Text = "Ragebot"
TextLabel14.TextColor = BrickColor.new("Br. yellowish green")
TextLabel14.TextColor3 = Color3.new(0.647059, 1, 0.360784)
TextLabel14.TextSize = 46
TextLabel14.TextXAlignment = Enum.TextXAlignment.Left
LocalScript15.Parent = TextLabel14
table.insert(cors,sandbox(LocalScript15,function()

while wait() do
	if script.Parent.Parent.Parent.Main.Tabs.Aim.Main.RageTab.Ragebot.BackgroundColor3 == Color3.fromRGB(181, 255, 42)
	then script.Parent.Visible = true
	end
	if script.Parent.Parent.Parent.Main.Tabs.Aim.Main.RageTab.Ragebot.BackgroundColor3 ~= Color3.fromRGB(181, 255, 42)
	then script.Parent.Visible = false
	end
end

end))
TextLabel16.Parent = TextLabel14
TextLabel16.Position = UDim2.new(0, 1, 0, 1)
TextLabel16.Size = UDim2.new(0, 200, 0, 42)
TextLabel16.BackgroundColor = BrickColor.new("Institutional white")
TextLabel16.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel16.BackgroundTransparency = 1
TextLabel16.Font = Enum.Font.SourceSansBold
TextLabel16.FontSize = Enum.FontSize.Size48
TextLabel16.Text = "Ragebot"
TextLabel16.TextColor = BrickColor.new("Really black")
TextLabel16.TextColor3 = Color3.new(0, 0, 0)
TextLabel16.TextSize = 46
TextLabel16.TextXAlignment = Enum.TextXAlignment.Left
Frame17.Name = "Main"
Frame17.Parent = ScreenGui0
Frame17.Position = UDim2.new(0.276864201, 0, 0.145037249, 0)
Frame17.Size = UDim2.new(0, 1141, 0, 1021)
Frame17.BackgroundColor = BrickColor.new("Really black")
Frame17.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
Frame17.BorderColor = BrickColor.new("Dirt brown")
Frame17.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame17.BorderSizePixel = 9
Frame17.ZIndex = 0
Frame18.Name = "Tabs"
Frame18.Parent = Frame17
Frame18.Size = UDim2.new(0, 163, 0, 1021)
Frame18.BackgroundColor = BrickColor.new("Really black")
Frame18.BackgroundColor3 = Color3.new(0, 0, 0)
Frame18.BorderColor = BrickColor.new("Dirt brown")
Frame18.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame18.BorderSizePixel = 0
Frame19.Name = "Aim"
Frame19.Parent = Frame18
Frame19.Size = UDim2.new(0, 163, 0, 142)
Frame19.BackgroundColor = BrickColor.new("Really black")
Frame19.BackgroundColor3 = Color3.new(0, 0, 0)
Frame19.BorderColor = BrickColor.new("Dirt brown")
Frame19.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame19.BorderSizePixel = 0
LocalScript20.Name = "Selected"
LocalScript20.Parent = Frame19
table.insert(cors,sandbox(LocalScript20,function()
local button = script.Parent.Icon


local function onMouseEntered()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.Icon.ImageColor3 ~= Color3.new(1, 1, 1)then
				script.Parent.Icon.ImageColor3 = Color3.new(1, 1, 1)
			end
		end
		button.Activated:Connect(onButtonActivated)
	end
	
end
local function onMouseLeft()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end

     
	
button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton21.Name = "Icon"
ImageButton21.Parent = Frame19
ImageButton21.Position = UDim2.new(0.104294479, 0, 0.104294479, 0)
ImageButton21.Size = UDim2.new(0, 128, 0, 128)
ImageButton21.BackgroundColor = BrickColor.new("Really black")
ImageButton21.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton21.BackgroundTransparency = 1
ImageButton21.BorderColor = BrickColor.new("Really black")
ImageButton21.BorderColor3 = Color3.new(0, 0, 0)
ImageButton21.ZIndex = 100
ImageButton21.Image = "rbxassetid://5750420886"
ImageButton21.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton21.ScaleType = Enum.ScaleType.Crop
Frame22.Name = "Side Border"
Frame22.Parent = Frame19
Frame22.Position = UDim2.new(1, 0, 0, 0)
Frame22.Size = UDim2.new(0, 3, 0, 145)
Frame22.BackgroundColor = BrickColor.new("Dirt brown")
Frame22.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame22.BorderSizePixel = 0
Frame22.ZIndex = 3
Frame23.Name = "Main"
Frame23.Parent = Frame19
Frame23.Position = UDim2.new(1.12883437, 0, 0.104294471, 0)
Frame23.Visible = false
Frame23.Size = UDim2.new(0, 941, 0, 993)
Frame23.BackgroundColor = BrickColor.new("Really red")
Frame23.BackgroundColor3 = Color3.new(1, 0, 0.0156863)
Frame23.BackgroundTransparency = 1
Frame23.BorderSizePixel = 0
Frame24.Name = "OtherTab"
Frame24.Parent = Frame23
Frame24.Position = UDim2.new(0.526000023, 0, 0.0320000015, 0)
Frame24.Size = UDim2.new(0, 424, 0, 953)
Frame24.BackgroundColor = BrickColor.new("Really black")
Frame24.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame24.BorderColor = BrickColor.new("Dirt brown")
Frame24.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame24.BorderSizePixel = 2
Frame25.Name = "DropDown"
Frame25.Parent = Frame24
Frame25.Position = UDim2.new(0.194999993, 0, 0.238000005, 0)
Frame25.Size = UDim2.new(0.612999976, 0, 0.0140000004, 0)
Frame25.BackgroundColor = BrickColor.new("Really black")
Frame25.BackgroundColor3 = Color3.new(0, 0, 0)
Frame25.BackgroundTransparency = 1
Frame25.BorderSizePixel = 0
Frame25.ZIndex = 3
TextButton26.Name = "Selection"
TextButton26.Parent = Frame25
TextButton26.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton26.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton26.BackgroundColor = BrickColor.new("Black")
TextButton26.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton26.BorderColor = BrickColor.new("Dirt brown")
TextButton26.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton26.BorderSizePixel = 3
TextButton26.Font = Enum.Font.SourceSans
TextButton26.FontSize = Enum.FontSize.Size28
TextButton26.Text = "[...]"
TextButton26.TextColor = BrickColor.new("Institutional white")
TextButton26.TextColor3 = Color3.new(1, 1, 1)
TextButton26.TextSize = 26
TextButton26.TextWrap = true
TextButton26.TextWrapped = true
Frame27.Name = "Menu"
Frame27.Parent = Frame25
Frame27.Position = UDim2.new(0, 0, -5.02099943, 3)
Frame27.Visible = false
Frame27.Size = UDim2.new(1, 0, 13.0922804, 0)
Frame27.BackgroundColor = BrickColor.new("Black")
Frame27.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame27.BorderColor = BrickColor.new("Dirt brown")
Frame27.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame27.BorderSizePixel = 3
Frame27.ZIndex = 2
TextButton28.Name = "Button5"
TextButton28.Parent = Frame27
TextButton28.Position = UDim2.new(0, 0, 0.798316538, 0)
TextButton28.Size = UDim2.new(1, 0, 0.00131385098, 35)
TextButton28.BackgroundColor = BrickColor.new("Black metallic")
TextButton28.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton28.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton28.BorderSizePixel = 0
TextButton28.ZIndex = 4
TextButton28.Font = Enum.Font.SourceSans
TextButton28.FontSize = Enum.FontSize.Size28
TextButton28.Text = "Maximum"
TextButton28.TextColor = BrickColor.new("Institutional white")
TextButton28.TextColor3 = Color3.new(1, 1, 1)
TextButton28.TextSize = 26
TextButton28.TextWrap = true
TextButton28.TextWrapped = true
TextButton29.Name = "Button4"
TextButton29.Parent = Frame27
TextButton29.Position = UDim2.new(0, 0, 0.598036706, 0)
TextButton29.Size = UDim2.new(1, 0, 0.00131385098, 35)
TextButton29.BackgroundColor = BrickColor.new("Black metallic")
TextButton29.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton29.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton29.BorderSizePixel = 0
TextButton29.ZIndex = 4
TextButton29.Font = Enum.Font.SourceSans
TextButton29.FontSize = Enum.FontSize.Size28
TextButton29.Text = "High"
TextButton29.TextColor = BrickColor.new("Institutional white")
TextButton29.TextColor3 = Color3.new(1, 1, 1)
TextButton29.TextSize = 26
TextButton29.TextWrap = true
TextButton29.TextWrapped = true
TextButton30.Name = "Button"
TextButton30.Parent = Frame27
TextButton30.Size = UDim2.new(1, 0, 0.00138687913, 35)
TextButton30.BackgroundColor = BrickColor.new("Black metallic")
TextButton30.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton30.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton30.BorderSizePixel = 0
TextButton30.ZIndex = 4
TextButton30.Font = Enum.Font.SourceSans
TextButton30.FontSize = Enum.FontSize.Size28
TextButton30.Text = "Super low"
TextButton30.TextColor = BrickColor.new("Institutional white")
TextButton30.TextColor3 = Color3.new(1, 1, 1)
TextButton30.TextSize = 26
TextButton30.TextWrap = true
TextButton30.TextWrapped = true
TextButton31.Name = "Button2"
TextButton31.Parent = Frame27
TextButton31.Position = UDim2.new(0, 0, 0.201756433, 0)
TextButton31.Size = UDim2.new(1, 0, -0.00459286617, 35)
TextButton31.BackgroundColor = BrickColor.new("Black metallic")
TextButton31.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton31.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton31.BorderSizePixel = 0
TextButton31.ZIndex = 4
TextButton31.Font = Enum.Font.SourceSans
TextButton31.FontSize = Enum.FontSize.Size28
TextButton31.Text = "Low"
TextButton31.TextColor = BrickColor.new("Institutional white")
TextButton31.TextColor3 = Color3.new(1, 1, 1)
TextButton31.TextSize = 26
TextButton31.TextWrap = true
TextButton31.TextWrapped = true
TextButton32.Name = "Button3"
TextButton32.Parent = Frame27
TextButton32.Position = UDim2.new(0, 0, 0.397533119, 0)
TextButton32.Size = UDim2.new(1, 0, 0.00131385098, 35)
TextButton32.BackgroundColor = BrickColor.new("Black metallic")
TextButton32.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton32.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton32.BorderSizePixel = 0
TextButton32.ZIndex = 4
TextButton32.Font = Enum.Font.SourceSans
TextButton32.FontSize = Enum.FontSize.Size28
TextButton32.Text = "Medium"
TextButton32.TextColor = BrickColor.new("Institutional white")
TextButton32.TextColor3 = Color3.new(1, 1, 1)
TextButton32.TextSize = 26
TextButton32.TextWrap = true
TextButton32.TextWrapped = true
LocalScript33.Name = "Effect"
LocalScript33.Parent = Frame25
table.insert(cors,sandbox(LocalScript33,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
ImageButton34.Name = "DT"
ImageButton34.Parent = Frame24
ImageButton34.Position = UDim2.new(0.0896415114, 0, 0.218473256, 0)
ImageButton34.Size = UDim2.new(0, 12, 0, 12)
ImageButton34.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton34.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton34.BorderColor = BrickColor.new("Really black")
ImageButton34.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton34.Image = "rbxassetid://5761429802"
ImageButton34.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton34.ImageTransparency = 0.25
TextLabel35.Name = "DT"
TextLabel35.Parent = ImageButton34
TextLabel35.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel35.Size = UDim2.new(0, 324, 0, 20)
TextLabel35.BackgroundColor = BrickColor.new("Institutional white")
TextLabel35.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel35.BackgroundTransparency = 1
TextLabel35.Font = Enum.Font.SourceSans
TextLabel35.FontSize = Enum.FontSize.Size28
TextLabel35.Text = "Double tap"
TextLabel35.TextColor = BrickColor.new("Institutional white")
TextLabel35.TextColor3 = Color3.new(1, 1, 1)
TextLabel35.TextSize = 26
TextLabel35.TextWrap = true
TextLabel35.TextWrapped = true
TextLabel35.TextXAlignment = Enum.TextXAlignment.Left
LocalScript36.Name = "DT"
LocalScript36.Parent = ImageButton34
table.insert(cors,sandbox(LocalScript36,function()
local button = script.Parent
local toggled = false

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)

	end
end
button.Activated:Connect(onButtonActivated)




end))
ImageButton37.Name = "Resolver"
ImageButton37.Parent = Frame24
ImageButton37.Position = UDim2.new(0.0896415114, 0, 0.256473243, 0)
ImageButton37.Size = UDim2.new(0, 12, 0, 12)
ImageButton37.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton37.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton37.BorderColor = BrickColor.new("Really black")
ImageButton37.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton37.Image = "rbxassetid://5761429802"
ImageButton37.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton37.ImageTransparency = 0.25
TextLabel38.Name = "Resolver"
TextLabel38.Parent = ImageButton37
TextLabel38.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel38.Size = UDim2.new(0, 324, 0, 20)
TextLabel38.BackgroundColor = BrickColor.new("Institutional white")
TextLabel38.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel38.BackgroundTransparency = 1
TextLabel38.Font = Enum.Font.SourceSans
TextLabel38.FontSize = Enum.FontSize.Size28
TextLabel38.Text = "Anti-aim correction"
TextLabel38.TextColor = BrickColor.new("Institutional white")
TextLabel38.TextColor3 = Color3.new(1, 1, 1)
TextLabel38.TextSize = 26
TextLabel38.TextWrap = true
TextLabel38.TextWrapped = true
TextLabel38.TextXAlignment = Enum.TextXAlignment.Left
LocalScript39.Name = "Resolver"
LocalScript39.Parent = ImageButton37
table.insert(cors,sandbox(LocalScript39,function()
local playerser=game:GetService("Players")
local plr=playerser.LocalPlayer
local TOGGLED = false

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
	--	game['Run Service'].Stepped:connect(function()
		--	if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
		--		for _,player in pairs(playerser:GetChildren()) do
		--			if player.Status.Team.Value ~= plr.Status.Team.Value and player.Character and player.Character:FindFirstChild"UpperTorso" and player.Character.UpperTorso:FindFirstChild"Waist" then
		--				player.Character.UpperTorso.Waist.C0 = CFrame.Angles(0,0,0)
		--			end
		--		end
	--		end
	--	end)
	end
end)



end))
ImageButton40.Name = "BT"
ImageButton40.Parent = Frame24
ImageButton40.Position = UDim2.new(0.0919811353, 0, 0.106049821, 0)
ImageButton40.Size = UDim2.new(0, 12, 0, 12)
ImageButton40.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton40.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton40.BorderColor = BrickColor.new("Really black")
ImageButton40.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton40.ZIndex = 2
ImageButton40.Image = "rbxassetid://5761429802"
ImageButton40.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton40.ImageTransparency = 0.25
TextLabel41.Name = "God"
TextLabel41.Parent = ImageButton40
TextLabel41.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel41.Size = UDim2.new(0, 324, 0, 20)
TextLabel41.BackgroundColor = BrickColor.new("Institutional white")
TextLabel41.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel41.BackgroundTransparency = 1
TextLabel41.Font = Enum.Font.SourceSans
TextLabel41.FontSize = Enum.FontSize.Size28
TextLabel41.Text = "Back track"
TextLabel41.TextColor = BrickColor.new("Institutional white")
TextLabel41.TextColor3 = Color3.new(1, 1, 1)
TextLabel41.TextSize = 26
TextLabel41.TextWrap = true
TextLabel41.TextWrapped = true
TextLabel41.TextXAlignment = Enum.TextXAlignment.Left
LocalScript42.Name = "BT"
LocalScript42.Parent = ImageButton40
table.insert(cors,sandbox(LocalScript42,function()
local button = script.Parent
local toggled = false
local color
local BTLEVEL = 0

local runserv = game:GetService("RunService")
runserv:BindToRenderStep("Rainbow", 1000, function()
	local hue = tick() % 5 / 5
	color = Color3.fromHSV(hue, 1, 1)
end)

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		if toggled == true then
			local BacktrackFolder = Instance.new("Folder")
			BacktrackFolder.Parent = workspace
			BacktrackFolder.Name = "BacktrackFolder"

			spawn(function()
				while toggled == true do
					wait(0.05)
					if script.Parent.Parent.DropDown.Selection.Text == "Super low" then
						BTLEVEL = 100
					end
					if script.Parent.Parent.DropDown.Selection.Text == "Low" then
						BTLEVEL = 250
					end
					if script.Parent.Parent.DropDown.Selection.Text == "Medium" then
						BTLEVEL = 500
					end
					if script.Parent.Parent.DropDown.Selection.Text == "High" then
						BTLEVEL = 1000
					end
					if script.Parent.Parent.DropDown.Selection.Text == "Maximum" then
						BTLEVEL = 2000
					end
					for i,v in pairs(game.Players:GetPlayers()) do
						pcall(function()
							if v.Character and v.Character.Humanoid and v.Character.Humanoid.Health > 0 and v.TeamColor ~= game.Players.LocalPlayer.TeamColor then
								local BacktrackPart = Instance.new("Part")
								BacktrackPart.Name = v.Name
								BacktrackPart.Anchored = true
								BacktrackPart.CanCollide = false
								BacktrackPart.Position = v.Character.Head.Position
								BacktrackPart.Orientation = v.Character.Head.Orientation
								BacktrackPart.Size = Vector3.new(1, 1, 1)
								BacktrackPart.Transparency = 0.5
								BacktrackPart.Color = color
								BacktrackPart.Material = Enum.Material.ForceField
								BacktrackPart.Parent = BacktrackFolder

								local BacktrackTag = Instance.new("ObjectValue")
								BacktrackTag.Parent = BacktrackPart
								BacktrackTag.Name = "PlayerName"
								BacktrackTag.Value = v

								spawn(function()
									wait(BTLEVEL/1000)
									BacktrackPart:Destroy()
								end)
							end
						end)
					end
				end
			end)
		end
		
		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)

	end
end
button.Activated:Connect(onButtonActivated)




end))
ImageButton43.Name = "RemoveSpread"
ImageButton43.Parent = Frame24
ImageButton43.Position = UDim2.new(0.0919811353, 0, 0.0329994522, 0)
ImageButton43.Size = UDim2.new(0, 12, 0, 12)
ImageButton43.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton43.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton43.BorderColor = BrickColor.new("Really black")
ImageButton43.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton43.ZIndex = 2
ImageButton43.Image = "rbxassetid://5761429802"
ImageButton43.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton43.ImageTransparency = 0.25
LocalScript44.Name = "idk"
LocalScript44.Parent = ImageButton43
table.insert(cors,sandbox(LocalScript44,function()
local button = script.Parent
local toggled = false
local client = getsenv(game.Players.LocalPlayer.PlayerGui.Client)

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		end
end

button.Activated:Connect(onButtonActivated)
		

end))
TextLabel45.Name = "Removespread"
TextLabel45.Parent = ImageButton43
TextLabel45.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel45.Size = UDim2.new(0, 324, 0, 20)
TextLabel45.BackgroundColor = BrickColor.new("Institutional white")
TextLabel45.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel45.BackgroundTransparency = 1
TextLabel45.Selectable = true
TextLabel45.Font = Enum.Font.SourceSans
TextLabel45.FontSize = Enum.FontSize.Size28
TextLabel45.Text = "Remove spread"
TextLabel45.TextColor = BrickColor.new("Institutional white")
TextLabel45.TextColor3 = Color3.new(1, 1, 1)
TextLabel45.TextSize = 26
TextLabel45.TextWrap = true
TextLabel45.TextWrapped = true
TextLabel45.TextXAlignment = Enum.TextXAlignment.Left
ImageButton46.Name = "RemoveRecoil"
ImageButton46.Parent = Frame24
ImageButton46.Position = UDim2.new(0.0919811353, 0, 0.0683391541, 0)
ImageButton46.Size = UDim2.new(0, 12, 0, 12)
ImageButton46.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton46.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton46.BorderColor = BrickColor.new("Really black")
ImageButton46.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton46.ZIndex = 2
ImageButton46.Image = "rbxassetid://5761429802"
ImageButton46.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton46.ImageTransparency = 0.25
LocalScript47.Name = "NoRecoil"
LocalScript47.Parent = ImageButton46
table.insert(cors,sandbox(LocalScript47,function()
local button = script.Parent
local toggled = false
local loop

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)	
	loop=game:GetService("RunService"):BindToRenderStep("NoRecoil", 100, function()
			local cbClient = getsenv(game.Players.LocalPlayer.PlayerGui.Client)
			cbClient.resetaccuracy()
			cbClient.RecoilX = 0
			cbClient.RecoilY = 0
		end)
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		loop:Disconnect()
	end
end
button.Activated:Connect(onButtonActivated)




end))
TextLabel48.Name = "Removerecoil"
TextLabel48.Parent = ImageButton46
TextLabel48.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel48.Size = UDim2.new(0, 324, 0, 20)
TextLabel48.BackgroundColor = BrickColor.new("Institutional white")
TextLabel48.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel48.BackgroundTransparency = 1
TextLabel48.Font = Enum.Font.SourceSans
TextLabel48.FontSize = Enum.FontSize.Size28
TextLabel48.Text = "Remove recoil"
TextLabel48.TextColor = BrickColor.new("Institutional white")
TextLabel48.TextColor3 = Color3.new(1, 1, 1)
TextLabel48.TextSize = 26
TextLabel48.TextWrap = true
TextLabel48.TextWrapped = true
TextLabel48.TextXAlignment = Enum.TextXAlignment.Left
TextLabel49.Name = "Other"
TextLabel49.Parent = Frame24
TextLabel49.Position = UDim2.new(0.0361394361, 0, -0.00979359634, 0)
TextLabel49.Size = UDim2.new(0, 65, 0, 10)
TextLabel49.Active = true
TextLabel49.BackgroundColor = BrickColor.new("Really black")
TextLabel49.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel49.BorderColor = BrickColor.new("Really black")
TextLabel49.BorderColor3 = Color3.new(0, 0, 0)
TextLabel49.BorderSizePixel = 0
TextLabel49.ZIndex = 2
TextLabel49.Font = Enum.Font.SourceSansBold
TextLabel49.FontSize = Enum.FontSize.Size28
TextLabel49.Text = "Other"
TextLabel49.TextColor = BrickColor.new("Mid gray")
TextLabel49.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel49.TextSize = 28
TextLabel49.TextWrap = true
TextLabel49.TextWrapped = true
Frame50.Name = "RageTab"
Frame50.Parent = Frame23
Frame50.Position = UDim2.new(0.0236982461, 0, 0.0315125808, 0)
Frame50.Size = UDim2.new(0, 424, 0, 953)
Frame50.BackgroundColor = BrickColor.new("Really black")
Frame50.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame50.BorderColor = BrickColor.new("Dirt brown")
Frame50.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame50.BorderSizePixel = 2
ImageButton51.Name = "Ragebot"
ImageButton51.Parent = Frame50
ImageButton51.Position = UDim2.new(0.0919811353, 0, 0.0329994522, 0)
ImageButton51.Size = UDim2.new(0, 12, 0, 12)
ImageButton51.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton51.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton51.BorderColor = BrickColor.new("Really black")
ImageButton51.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton51.ZIndex = 2
ImageButton51.Image = "rbxassetid://5761429802"
ImageButton51.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton51.ImageTransparency = 0.25
TextLabel52.Name = "name"
TextLabel52.Parent = ImageButton51
TextLabel52.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel52.Size = UDim2.new(0, 324, 0, 20)
TextLabel52.BackgroundColor = BrickColor.new("Institutional white")
TextLabel52.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel52.BackgroundTransparency = 1
TextLabel52.Selectable = true
TextLabel52.Font = Enum.Font.SourceSans
TextLabel52.FontSize = Enum.FontSize.Size28
TextLabel52.Text = "Rage bot"
TextLabel52.TextColor = BrickColor.new("Institutional white")
TextLabel52.TextColor3 = Color3.new(1, 1, 1)
TextLabel52.TextSize = 26
TextLabel52.TextWrap = true
TextLabel52.TextWrapped = true
TextLabel52.TextXAlignment = Enum.TextXAlignment.Left
LocalScript53.Name = "Ragebot"
LocalScript53.Parent = ImageButton51
table.insert(cors,sandbox(LocalScript53,function()
-- Services
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local repstor = game:GetService("ReplicatedStorage")
local runserv = game:GetService("RunService")

-- Variables
local cam = workspace.CurrentCamera
local client = getsenv(plr.PlayerGui.Client)
local mindamage = script.Parent.Parent.Background.Percent.Value

-- Metatables and Silent aim
local mt = getrawmetatable(game)
setreadonly(mt,false)
local nc = mt.__namecall

--Random
local rage = false
local button = script.Parent

--Prevents rapidfire
function coolDown()
	shootCooldown = true
	if game.ReplicatedStorage.Weapons:FindFirstChild(tostring(client.gun)) then
		wait(game.ReplicatedStorage.Weapons:FindFirstChild(tostring(client.gun)).FireRate.Value)
		shootCooldown = false
	end
end

--Hitpart
function HitPart(target)
	local Remote = game.ReplicatedStorage.Events['HitPart']
	local Arguments = {
		[1] = target.Character.HeadHB,
		[2] = target.Character.HeadHB.CFrame.p,
		[3] = workspace[game.Players.LocalPlayer.Name].EquippedTool.Value,
		[4] = tonumber(script.Parent.Parent.Background1.Bar.Button.ValueText.Text),
		[5] = workspace[game.Players.LocalPlayer.Name].Gun,
		[8] = 1,
		[9] = false,
		[10] = false,
		[11] = Vector3.new(),
		[12] = 100,
		[13] = Vector3.new()
	}
	Remote:FireServer(unpack(Arguments))
end

--Firebullet
function fireBullet()
	if not shootCooldown then
		client.firebullet()
		coolDown()
	end
end

--Boosted damage
function hook_Hitpart(target)
	if not shootCooldown then
		HitPart(target)
		coolDown()	
	end	
end

--Doubletap
function Doubletap()
	if not shootCooldown then
		client.firebullet()
		client.firebullet()
		coolDown()
	end
end

--BulletTracers
function traceBullet(pos)
	local tracer = Instance.new("Part",game.Workspace.Debris)
	tracer.BrickColor = Color3.fromRGB(255, 58, 236)
	tracer.Material = Enum.Material.ForceField
	tracer.Anchored = true
	tracer.CanCollide = false
	local distance = (plr.Character.Gun.Flash.CFrame.p - pos).magnitude
	tracer.Size = Vector3.new(0.1, 0.1, distance)
	tracer.CFrame = CFrame.new(plr.Character.Head.CFrame.p, pos) * CFrame.new(0, 0, -distance / 2)
	game:GetService("Debris"):AddItem(tracer, 0.5)
end


--Autowall to the Head
function simulateHeadShot(target)
	local hitList = {
		cam,
		plr.Character,
		game.Workspace.Debris,
		game.Workspace.Ray_Ignore,
		game.Workspace.Map:WaitForChild("Clips"),
		game.Workspace.Map:WaitForChild("SpawnPoints"),
	}
	local gun = client.gun
	local gunPen,gunRange,gunDMG
	if gun:FindFirstChild("Penetration") then
		gunPen = gun.Penetration.Value * 0.01
	end
	if gun:FindFirstChild("Range") then
		gunRange = gun.Range.Value*4
	end
	if gun:FindFirstChild("DMG") then
		gunDMG = (gun.DMG.Value)*3
	end
	local direction = CFrame.new(cam.CFrame.p, target.Character.Head.Position).lookVector.unit * gunRange * 0.0694
	local rayCasted = Ray.new(cam.CFrame.p, direction)
	local hitPart, hitPos = workspace:FindPartOnRayWithIgnoreList(rayCasted, hitList, false, true)
	local partPenetrated = 0
	local limit = 0
	local partHit, posHit, normHit
	local partModifier = 1
	local damageModifier = 1
	repeat
		partHit, posHit, normHit = workspace:FindPartOnRayWithIgnoreList(rayCasted, hitList, false, true)
		if partHit and partHit.Parent then
			partModifier = 1
			if partHit.Material == Enum.Material.DiamondPlate then
				partModifier = 3
			elseif partHit.Material == Enum.Material.CorrodedMetal or partHit.Material == Enum.Material.Metal or partHit.Material == Enum.Material.Concrete or partHit.Material == Enum.Material.Brick then
				partModifier = 2
			elseif partHit.Name == "Grate" or partHit.Material == Enum.Material.Wood or partHit.Material == Enum.Material.WoodPlanks then
				partModifier = 0.1
			elseif partHit.Transparency == 1 or partHit.CanCollide == false or partHit.Name == "Glass" or partHit.Name == "Cardboard" or partHit:IsDescendantOf(game.Workspace.Ray_Ignore) or partHit:IsDescendantOf(game.Workspace.Debris) then
				partModifier = 0
			elseif partHit.Name == "nowallbang" then
				partModifier = 100
			elseif partHit:FindFirstChild("PartModifier") then
				partModifier = partHit.PartModifier.Value
			end
			local fakeHit, fakePos = workspace:FindPartOnRayWithWhitelist(Ray.new(posHit + direction * 1, direction * -2), {partHit}, true)
			local penDistance = (fakePos - posHit).magnitude
			penDistance = penDistance * partModifier
			limit = math.min(gunPen, limit + penDistance)
			local wallbang = false
			if partPenetrated >= 1 then
				wallbang = true
			end
			if partHit and partHit.Parent and partHit.Parent.Name == "Hitboxes" or partHit and partHit.Parent.className == "Accessory" or partHit and partHit.Parent.className == "Hat" and partHit.Parent.Name ~= "Door" and partHit.Parent:FindFirstChild("Hostage") == nil then
			else
				if partHit and partHit:IsDescendantOf(target.Character) and partHit.Transparency < 1 or partHit.Name == "HeadHB" then
					return partHit, posHit, damageModifier, wallbang
				end
			end
			damageModifier = 1 - limit / gunPen
			if partModifier > 0 then
				partPenetrated = partPenetrated + 1
			end
			if partHit and partHit.Parent and partHit.Parent.Name == "Hitboxes" or partHit and partHit.Parent and partHit.Parent.Parent and partHit.Parent.Parent:FindFirstChild("Humanoid2") or partHit and partHit.Parent and partHit.Parent:FindFirstChild("Humanoid2") or partHit and partHit.Parent and partHit.Parent:FindFirstChild("Humanoid") and partHit.Parent:IsA("Model") then
				table.insert(hitList, partHit.Parent)
			else
				table.insert(hitList, partHit)
			end
		end
	until partHit == nil or partHit.Parent == target.Character or limit >= gunPen or 0 >= damageModifier or partPenetrated >= 4
end


--Autowall to the Body
function simulateBodyShot(target)
	local hitList = {
		cam,
		plr.Character,
		game.Workspace.Debris,
		game.Workspace.Ray_Ignore,
		game.Workspace.Map:WaitForChild("Clips"),
		game.Workspace.Map:WaitForChild("SpawnPoints"),
	}
	local gun = client.gun
	local gunPen,gunRange,gunDMG
	if gun:FindFirstChild("Penetration") then
		gunPen = gun.Penetration.Value * 0.01
	end
	if gun:FindFirstChild("Range") then
		gunRange = gun.Range.Value*4
	end
	if gun:FindFirstChild("DMG") then
		gunDMG = gun.DMG.Value
	end
	local direction = CFrame.new(cam.CFrame.p, target.Character.LowerTorso.Position).lookVector.unit * gunRange * 0.0694
	local rayCasted = Ray.new(cam.CFrame.p, direction)
	local hitPart, hitPos = workspace:FindPartOnRayWithIgnoreList(rayCasted, hitList, false, true)
	local partPenetrated = 0
	local limit = 0
	local partHit, posHit, normHit
	local partModifier = 1
	local damageModifier = 1
	repeat
		partHit, posHit, normHit = workspace:FindPartOnRayWithIgnoreList(rayCasted, hitList, false, true)
		if partHit and partHit.Parent then
			partModifier = 1
			if partHit.Material == Enum.Material.DiamondPlate then
				partModifier = 3
			elseif partHit.Material == Enum.Material.CorrodedMetal or partHit.Material == Enum.Material.Metal or partHit.Material == Enum.Material.Concrete or partHit.Material == Enum.Material.Brick then
				partModifier = 2
			elseif partHit.Name == "Grate" or partHit.Material == Enum.Material.Wood or partHit.Material == Enum.Material.WoodPlanks then
				partModifier = 0.1
			elseif partHit.Transparency == 1 or partHit.CanCollide == false or partHit.Name == "Glass" or partHit.Name == "Cardboard" or partHit:IsDescendantOf(game.Workspace.Ray_Ignore) or partHit:IsDescendantOf(game.Workspace.Debris) then
				partModifier = 0
			elseif partHit.Name == "nowallbang" then
				partModifier = 100
			elseif partHit:FindFirstChild("PartModifier") then
				partModifier = partHit.PartModifier.Value
			end
			local fakeHit, fakePos = workspace:FindPartOnRayWithWhitelist(Ray.new(posHit + direction * 1, direction * -2), {partHit}, true)
			local penDistance = (fakePos - posHit).magnitude
			penDistance = penDistance * partModifier
			limit = math.min(gunPen, limit + penDistance)
			local wallbang = false
			if partPenetrated >= 1 then
				wallbang = true
			end
			if partHit and partHit.Parent and partHit.Parent.Name == "Hitboxes" or partHit and partHit.Parent.className == "Accessory" or partHit and partHit.Parent.className == "Hat" and partHit.Parent.Name ~= "Door" and partHit.Parent:FindFirstChild("Hostage") == nil then
			else
				if partHit and partHit:IsDescendantOf(target.Character) and partHit.Transparency < 1 or partHit.Name == "HeadHB" then
					return partHit, posHit, damageModifier, wallbang
				end
			end
			damageModifier = 1 - limit / gunPen
			if partModifier > 0 then
				partPenetrated = partPenetrated + 1
			end
			if partHit and partHit.Parent and partHit.Parent.Name == "Hitboxes" or partHit and partHit.Parent and partHit.Parent.Parent and partHit.Parent.Parent:FindFirstChild("Humanoid2") or partHit and partHit.Parent and partHit.Parent:FindFirstChild("Humanoid2") or partHit and partHit.Parent and partHit.Parent:FindFirstChild("Humanoid") and partHit.Parent:IsA("Model") then
				table.insert(hitList, partHit.Parent)
			else
				table.insert(hitList, partHit)
			end
		end
	until partHit == nil or partHit.Parent == target.Character or limit >= gunPen or 0 >= damageModifier or partPenetrated >= 4
end
	


local function onButtonActivated()
	if rage == false then
		rage = true
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		runserv.RenderStepped:Connect(function()
			if rage and plr.Character and plr.Character:FindFirstChild("HumanoidRootPart") then
				for i,v in next,plrs:GetPlayers() do
					if v ~= plr and v.Character and v.Character:FindFirstChild("HumanoidRootPart") and v.TeamColor ~= game.Players.LocalPlayer.TeamColor then
						pcall(function()
						local partHit, posHit, damageModifier, wallbang = simulateHeadShot(v)
							local partHit2, posHit2, damageModifier2, wallbang2 = simulateBodyShot(v)
							if partHit and (damageModifier * client.gun.DMG.Value) > mindamage or partHit2 and (damageModifier2 * client.gun.DMG.Value) > mindamage then
									if (damageModifier * client.gun.DMG.Value) >= (damageModifier2 * client.gun.DMG.Value) then
											target = partHit
											script.Firing.Value = true
											mt.__namecall = newcclosure(
												function(self,...)
													local args = {...}
													local namecall = getnamecallmethod()
													if namecall == "FindPartOnRayWithIgnoreList" then
														if target and plr.Character and rage then
															args[1] = Ray.new(workspace.CurrentCamera.CFrame.p, (target.CFrame.p - workspace.CurrentCamera.CFrame.p).unit * 500)
														end
													end
													return nc(self,unpack(args))
												end
											)
											if script.Parent.Parent.Hitpart.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
												hook_Hitpart(v)
											end
											if script.Parent.Parent.Parent.OtherTab.DT.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
												Doubletap()
											end
											fireBullet()
											script.Firing.Value = false		
										else
											target = partHit2
											script.Firing.Value = true
											mt.__namecall = newcclosure(
												function(self,...)
													local args = {...}
													local namecall = getnamecallmethod()
													if namecall == "FindPartOnRayWithIgnoreList" then
														if target and plr.Character and rage then
															args[1] = Ray.new(workspace.CurrentCamera.CFrame.p, (target.CFrame.p - workspace.CurrentCamera.CFrame.p).unit * 500)
														end
													end
													return nc(self,unpack(args))
												end
											)
											if script.Parent.Parent.Hitpart.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
												hook_Hitpart(v)
											end
											if script.Parent.Parent.Parent.OtherTab.DT.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
												Doubletap()
											end
											fireBullet()
											script.Firing.Value = false		
										end
									else
								target = nil
							end
						end)
					end
				end
			end
		end)
	else
		rage = false
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
	end
end

button.Activated:Connect(onButtonActivated)
end))
BoolValue54.Name = "Firing"
BoolValue54.Parent = LocalScript53
TextLabel55.Name = "Aimbot"
TextLabel55.Parent = Frame50
TextLabel55.Position = UDim2.new(0.0361394361, 0, -0.00979359634, 0)
TextLabel55.Size = UDim2.new(0, 83, 0, 10)
TextLabel55.Active = true
TextLabel55.BackgroundColor = BrickColor.new("Really black")
TextLabel55.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel55.BorderColor = BrickColor.new("Really black")
TextLabel55.BorderColor3 = Color3.new(0, 0, 0)
TextLabel55.BorderSizePixel = 0
TextLabel55.ZIndex = 2
TextLabel55.Font = Enum.Font.SourceSansBold
TextLabel55.FontSize = Enum.FontSize.Size28
TextLabel55.Text = "Aimbot"
TextLabel55.TextColor = BrickColor.new("Mid gray")
TextLabel55.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel55.TextSize = 28
TextLabel55.TextWrap = true
TextLabel55.TextWrapped = true
Frame56.Name = "Background"
Frame56.Parent = Frame50
Frame56.Position = UDim2.new(0.551716983, -150, 0.13302204, 0)
Frame56.Size = UDim2.new(0, 259, 0, 27)
Frame56.BackgroundColor = BrickColor.new("Really black")
Frame56.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame56.BorderSizePixel = 0
Frame57.Name = "Bar"
Frame57.Parent = Frame56
Frame57.Position = UDim2.new(0, 0, 0.296296299, 0)
Frame57.Size = UDim2.new(0, 255, 0, 10)
Frame57.BackgroundColor = BrickColor.new("Dark taupe")
Frame57.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
Frame57.BorderSizePixel = 0
TextButton58.Name = "Button"
TextButton58.Parent = Frame57
TextButton58.Position = UDim2.new(0, 0, 0, -10)
TextButton58.Size = UDim2.new(0, 30, 0, 30)
TextButton58.BackgroundColor = BrickColor.new("Institutional white")
TextButton58.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton58.BorderSizePixel = 0
TextButton58.Draggable = true
TextButton58.Style = Enum.ButtonStyle.RobloxRoundButton
TextButton58.Font = Enum.Font.SourceSans
TextButton58.FontSize = Enum.FontSize.Size14
TextButton58.Text = ""
TextButton58.TextSize = 14
LocalScript59.Name = "Slider"
LocalScript59.Parent = TextButton58
table.insert(cors,sandbox(LocalScript59,function()
-- REMEMBER THIS! You can only drag a gui in offset and not scale!

local sp = script.Parent
local bar = sp.Parent
local percent = sp.Parent.Parent.Percent
local run = game:GetService("RunService")

-- get original position
local xpos = {sp.Position.X.Scale, sp.Position.X.Offset}
local ypos = {sp.Position.Y.Scale, sp.Position.Y.Offset}

run.RenderStepped:connect(function()
	sp.Position = UDim2.new(sp.Position.X.Scale, sp.Position.X.Offset , ypos[1], ypos[2])
	if sp.Position.X.Offset >= bar.Size.X.Offset - sp.Size.X.Offset then -- triggered when the button goes over the bar's size
		sp.Position = UDim2.new(sp.Position.X.Scale, (bar.Size.X.Offset - sp.Size.X.Offset) , ypos[1], ypos[2])
	elseif sp.Position.X.Offset <= 0 then -- triggered when the button's position goes negative
		sp.Position = UDim2.new(xpos[1], xpos[2] , ypos[1], ypos[2])
	end

	percent.Value = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100)
	sp.ValueText.Text = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100)
end)

end))
TextLabel60.Name = "ValueText"
TextLabel60.Parent = TextButton58
TextLabel60.Position = UDim2.new(-2, 0, 0.787, 0)
TextLabel60.Size = UDim2.new(0, 30, 0, 37)
TextLabel60.BackgroundColor = BrickColor.new("Institutional white")
TextLabel60.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel60.BackgroundTransparency = 1
TextLabel60.Font = Enum.Font.SourceSans
TextLabel60.FontSize = Enum.FontSize.Size24
TextLabel60.Text = "0"
TextLabel60.TextColor = BrickColor.new("Institutional white")
TextLabel60.TextColor3 = Color3.new(1, 1, 1)
TextLabel60.TextSize = 24
NumberValue61.Name = "Percent"
NumberValue61.Parent = Frame56
ImageButton62.Name = "HitpartDMG"
ImageButton62.Parent = Frame50
ImageButton62.Position = UDim2.new(0.094339624, 0, 0.187249169, 0)
ImageButton62.Size = UDim2.new(0, 12, 0, 12)
ImageButton62.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton62.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton62.BackgroundTransparency = 1
ImageButton62.BorderColor = BrickColor.new("Really black")
ImageButton62.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton62.ZIndex = 2
ImageButton62.Image = "rbxassetid://5761429802"
ImageButton62.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton62.ImageTransparency = 1
TextLabel63.Name = "HITPARTDMG"
TextLabel63.Parent = ImageButton62
TextLabel63.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel63.Size = UDim2.new(0, 324, 0, 20)
TextLabel63.BackgroundColor = BrickColor.new("Institutional white")
TextLabel63.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel63.BackgroundTransparency = 1
TextLabel63.Selectable = true
TextLabel63.Font = Enum.Font.SourceSans
TextLabel63.FontSize = Enum.FontSize.Size28
TextLabel63.Text = "Hitpart Damage"
TextLabel63.TextColor = BrickColor.new("Institutional white")
TextLabel63.TextColor3 = Color3.new(1, 1, 1)
TextLabel63.TextSize = 26
TextLabel63.TextWrap = true
TextLabel63.TextWrapped = true
TextLabel63.TextXAlignment = Enum.TextXAlignment.Left
ImageButton64.Name = "Origin"
ImageButton64.Parent = Frame50
ImageButton64.Position = UDim2.new(0.0900000036, 0, 0.271178424, 0)
ImageButton64.Size = UDim2.new(0, 12, 0, 12)
ImageButton64.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton64.BackgroundColor3 = Color3.new(0.286275, 0.286275, 0.286275)
ImageButton64.BackgroundTransparency = 1
ImageButton64.BorderColor = BrickColor.new("Really black")
ImageButton64.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton64.ZIndex = 2
ImageButton64.Image = "rbxassetid://5761429802"
ImageButton64.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton64.ImageTransparency = 1
TextLabel65.Name = "MinDmg"
TextLabel65.Parent = ImageButton64
TextLabel65.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel65.Size = UDim2.new(0, 324, 0, 20)
TextLabel65.BackgroundColor = BrickColor.new("Institutional white")
TextLabel65.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel65.BackgroundTransparency = 1
TextLabel65.Selectable = true
TextLabel65.Font = Enum.Font.SourceSans
TextLabel65.FontSize = Enum.FontSize.Size28
TextLabel65.Text = "Aimbot origin"
TextLabel65.TextColor = BrickColor.new("Institutional white")
TextLabel65.TextColor3 = Color3.new(1, 1, 1)
TextLabel65.TextSize = 26
TextLabel65.TextWrap = true
TextLabel65.TextWrapped = true
TextLabel65.TextXAlignment = Enum.TextXAlignment.Left
Frame66.Name = "DropDown"
Frame66.Parent = Frame50
Frame66.Position = UDim2.new(0.197358489, 0, 0.392770231, 0)
Frame66.Size = UDim2.new(0.612999976, 0, 0.0140000004, 0)
Frame66.BackgroundColor = BrickColor.new("Really black")
Frame66.BackgroundColor3 = Color3.new(0, 0, 0)
Frame66.BackgroundTransparency = 1
Frame66.BorderSizePixel = 0
Frame66.ZIndex = 3
TextButton67.Name = "Selection"
TextButton67.Parent = Frame66
TextButton67.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton67.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton67.BackgroundColor = BrickColor.new("Black")
TextButton67.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton67.BorderColor = BrickColor.new("Dirt brown")
TextButton67.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton67.BorderSizePixel = 3
TextButton67.Font = Enum.Font.SourceSans
TextButton67.FontSize = Enum.FontSize.Size28
TextButton67.Text = "[...]"
TextButton67.TextColor = BrickColor.new("Institutional white")
TextButton67.TextColor3 = Color3.new(1, 1, 1)
TextButton67.TextSize = 26
TextButton67.TextWrap = true
TextButton67.TextWrapped = true
Frame68.Name = "Menu"
Frame68.Parent = Frame66
Frame68.Position = UDim2.new(0, 0, -5.02099705, 3)
Frame68.Visible = false
Frame68.Size = UDim2.new(1, 0, 5.36823606, 0)
Frame68.BackgroundColor = BrickColor.new("Black")
Frame68.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame68.BorderColor = BrickColor.new("Dirt brown")
Frame68.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame68.BorderSizePixel = 3
Frame68.ZIndex = 2
TextButton69.Name = "Button"
TextButton69.Parent = Frame68
TextButton69.Position = UDim2.new(0, 0, -0.0170579366, 0)
TextButton69.Size = UDim2.new(1, 0, 0.0188986287, 35)
TextButton69.BackgroundColor = BrickColor.new("Black metallic")
TextButton69.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton69.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton69.BorderSizePixel = 0
TextButton69.ZIndex = 4
TextButton69.Font = Enum.Font.SourceSans
TextButton69.FontSize = Enum.FontSize.Size28
TextButton69.Text = "Camera"
TextButton69.TextColor = BrickColor.new("Institutional white")
TextButton69.TextColor3 = Color3.new(1, 1, 1)
TextButton69.TextSize = 26
TextButton69.TextWrap = true
TextButton69.TextWrapped = true
TextButton70.Name = "Button2"
TextButton70.Parent = Frame68
TextButton70.Position = UDim2.new(0, 0, 0.497701526, 0)
TextButton70.Size = UDim2.new(1, 0, 0.0127051994, 35)
TextButton70.BackgroundColor = BrickColor.new("Black metallic")
TextButton70.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton70.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton70.BorderSizePixel = 0
TextButton70.ZIndex = 4
TextButton70.Font = Enum.Font.SourceSans
TextButton70.FontSize = Enum.FontSize.Size28
TextButton70.Text = "Head"
TextButton70.TextColor = BrickColor.new("Institutional white")
TextButton70.TextColor3 = Color3.new(1, 1, 1)
TextButton70.TextSize = 26
TextButton70.TextWrap = true
TextButton70.TextWrapped = true
LocalScript71.Name = "Effect"
LocalScript71.Parent = Frame66
table.insert(cors,sandbox(LocalScript71,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then

		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else

		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
ImageButton72.Name = "Hitpart"
ImageButton72.Parent = Frame50
ImageButton72.Position = UDim2.new(0.0919811353, 0, 0.0686762631, 0)
ImageButton72.Size = UDim2.new(0, 12, 0, 12)
ImageButton72.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton72.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton72.BorderColor = BrickColor.new("Really black")
ImageButton72.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton72.ZIndex = 2
ImageButton72.Image = "rbxassetid://5761429802"
ImageButton72.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton72.ImageTransparency = 0.25
TextLabel73.Name = "name"
TextLabel73.Parent = ImageButton72
TextLabel73.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel73.Size = UDim2.new(0, 324, 0, 20)
TextLabel73.BackgroundColor = BrickColor.new("Institutional white")
TextLabel73.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel73.BackgroundTransparency = 1
TextLabel73.Selectable = true
TextLabel73.Font = Enum.Font.SourceSans
TextLabel73.FontSize = Enum.FontSize.Size28
TextLabel73.Text = "Hitpart"
TextLabel73.TextColor = BrickColor.new("Institutional white")
TextLabel73.TextColor3 = Color3.new(1, 1, 1)
TextLabel73.TextSize = 26
TextLabel73.TextWrap = true
TextLabel73.TextWrapped = true
TextLabel73.TextXAlignment = Enum.TextXAlignment.Left
LocalScript74.Name = "toggle"
LocalScript74.Parent = ImageButton72
table.insert(cors,sandbox(LocalScript74,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)

	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
	
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton75.Name = "MinDmg"
ImageButton75.Parent = Frame50
ImageButton75.Position = UDim2.new(0.094339624, 0, 0.106451705, 0)
ImageButton75.Size = UDim2.new(0, 12, 0, 12)
ImageButton75.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton75.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton75.BackgroundTransparency = 1
ImageButton75.BorderColor = BrickColor.new("Really black")
ImageButton75.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton75.ZIndex = 2
ImageButton75.Image = "rbxassetid://5761429802"
ImageButton75.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton75.ImageTransparency = 1
TextLabel76.Name = "MinDmg"
TextLabel76.Parent = ImageButton75
TextLabel76.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel76.Size = UDim2.new(0, 324, 0, 20)
TextLabel76.BackgroundColor = BrickColor.new("Institutional white")
TextLabel76.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel76.BackgroundTransparency = 1
TextLabel76.Selectable = true
TextLabel76.Font = Enum.Font.SourceSans
TextLabel76.FontSize = Enum.FontSize.Size28
TextLabel76.Text = "Minimum damage"
TextLabel76.TextColor = BrickColor.new("Institutional white")
TextLabel76.TextColor3 = Color3.new(1, 1, 1)
TextLabel76.TextSize = 26
TextLabel76.TextWrap = true
TextLabel76.TextWrapped = true
TextLabel76.TextXAlignment = Enum.TextXAlignment.Left
Frame77.Name = "Background1"
Frame77.Parent = Frame50
Frame77.Position = UDim2.new(0.549358487, -150, 0.211720869, 0)
Frame77.Size = UDim2.new(0, 259, 0, 27)
Frame77.BackgroundColor = BrickColor.new("Really black")
Frame77.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame77.BorderSizePixel = 0
Frame78.Name = "Bar"
Frame78.Parent = Frame77
Frame78.Position = UDim2.new(0, 0, 0.296296299, 0)
Frame78.Size = UDim2.new(0, 255, 0, 10)
Frame78.BackgroundColor = BrickColor.new("Dark taupe")
Frame78.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
Frame78.BorderSizePixel = 0
TextButton79.Name = "Button"
TextButton79.Parent = Frame78
TextButton79.Position = UDim2.new(0, 0, 0, -10)
TextButton79.Size = UDim2.new(0, 30, 0, 30)
TextButton79.BackgroundColor = BrickColor.new("Institutional white")
TextButton79.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton79.BorderSizePixel = 0
TextButton79.Draggable = true
TextButton79.Style = Enum.ButtonStyle.RobloxRoundButton
TextButton79.Font = Enum.Font.SourceSans
TextButton79.FontSize = Enum.FontSize.Size14
TextButton79.Text = ""
TextButton79.TextSize = 14
LocalScript80.Name = "Slider"
LocalScript80.Parent = TextButton79
table.insert(cors,sandbox(LocalScript80,function()
-- REMEMBER THIS! You can only drag a gui in offset and not scale!

local sp = script.Parent
local bar = sp.Parent
local percent = sp.Parent.Parent.Percent
local run = game:GetService("RunService")

-- get original position
local xpos = {sp.Position.X.Scale, sp.Position.X.Offset}
local ypos = {sp.Position.Y.Scale, sp.Position.Y.Offset}

run.RenderStepped:connect(function()
	sp.Position = UDim2.new(sp.Position.X.Scale, sp.Position.X.Offset , ypos[1], ypos[2])
	if sp.Position.X.Offset >= bar.Size.X.Offset - sp.Size.X.Offset then -- triggered when the button goes over the bar's size
		sp.Position = UDim2.new(sp.Position.X.Scale, (bar.Size.X.Offset - sp.Size.X.Offset) , ypos[1], ypos[2])
	elseif sp.Position.X.Offset <= 0 then -- triggered when the button's position goes negative
		sp.Position = UDim2.new(xpos[1], xpos[2] , ypos[1], ypos[2])
	end

	percent.Value = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100)
	sp.ValueText.Text = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100)
end)

end))
TextLabel81.Name = "ValueText"
TextLabel81.Parent = TextButton79
TextLabel81.Position = UDim2.new(-2, 0, 0.787, 0)
TextLabel81.Size = UDim2.new(0, 30, 0, 37)
TextLabel81.BackgroundColor = BrickColor.new("Institutional white")
TextLabel81.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel81.BackgroundTransparency = 1
TextLabel81.Font = Enum.Font.SourceSans
TextLabel81.FontSize = Enum.FontSize.Size24
TextLabel81.Text = "0"
TextLabel81.TextColor = BrickColor.new("Institutional white")
TextLabel81.TextColor3 = Color3.new(1, 1, 1)
TextLabel81.TextSize = 24
NumberValue82.Name = "Percent"
NumberValue82.Parent = Frame77
Frame83.Name = "Visual"
Frame83.Parent = Frame18
Frame83.Position = UDim2.new(0, 0, 0.425989151, 0)
Frame83.Size = UDim2.new(0, 163, 0, 142)
Frame83.BackgroundColor = BrickColor.new("Really black")
Frame83.BackgroundColor3 = Color3.new(0, 0, 0)
Frame83.BorderColor = BrickColor.new("Really black")
Frame83.BorderColor3 = Color3.new(0, 0, 0)
Frame83.BorderSizePixel = 0
LocalScript84.Name = "Selected"
LocalScript84.Parent = Frame83
table.insert(cors,sandbox(LocalScript84,function()
local button = script.Parent.Icon


local function onMouseEntered()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.Icon.ImageColor3 ~= Color3.new(1, 1, 1)then
				script.Parent.Icon.ImageColor3 = Color3.new(1, 1, 1)
			end
		end
		button.Activated:Connect(onButtonActivated)
	end
	
end
local function onMouseLeft()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end

     
	
button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
Frame85.Name = "Main"
Frame85.Parent = Frame83
Frame85.Position = UDim2.new(1.12899995, 0, -2.96499991, 0)
Frame85.Visible = false
Frame85.Size = UDim2.new(0, 941, 0, 993)
Frame85.BackgroundColor = BrickColor.new("New Yeller")
Frame85.BackgroundColor3 = Color3.new(1, 0.933333, 0)
Frame85.BackgroundTransparency = 1
Frame85.BorderSizePixel = 0
Frame86.Name = "ColoredmodelsTab"
Frame86.Parent = Frame85
Frame86.Position = UDim2.new(0.0233433209, 0, 0.713618994, 0)
Frame86.Size = UDim2.new(0, 424, 0, 274)
Frame86.BackgroundColor = BrickColor.new("Really black")
Frame86.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame86.BorderColor = BrickColor.new("Dirt brown")
Frame86.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame86.BorderSizePixel = 2
ImageButton87.Name = "OuterChams"
ImageButton87.Parent = Frame86
ImageButton87.Position = UDim2.new(0.0920000002, 0, 0.225999996, 0)
ImageButton87.Size = UDim2.new(0, 12, 0, 12)
ImageButton87.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton87.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton87.BorderColor = BrickColor.new("Really black")
ImageButton87.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton87.ZIndex = 999
ImageButton87.Image = "rbxassetid://5761429802"
ImageButton87.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton87.ImageTransparency = 0.25
LocalScript88.Name = "OuterChams"
LocalScript88.Parent = ImageButton87
table.insert(cors,sandbox(LocalScript88,function()
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local button = script.Parent
local toggled = false
local espFolder = Instance.new("Folder",game.CoreGui)
local color = script.Parent.Color.BackgroundColor3
function chamPlr(plr)
	if plr.Character then
		for i,v in next,plr.Character:GetChildren() do
			if v:IsA("BasePart") and v.Name ~= "HumanoidRootPart" and v.Name ~= "Gun" then
				local chamThing = Instance.new("BoxHandleAdornment",espFolder)
				chamThing.Size = v.Size + Vector3.new(0.2, 0.2, 0.2)
				chamThing.Transparency = 0.1
				chamThing.ZIndex = -2
				chamThing.AlwaysOnTop = false
				chamThing.Visible = true
				chamThing.Adornee = v
				chamThing.Color3 = color
				plr.Character.HumanoidRootPart.AncestryChanged:connect(function()
					chamThing:Destroy()
				end)
			end
		end
	end
end



local function onButtonActivated()
	if toggled == false then
		toggled = true
		local plrChams = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		for i,v in next,plrs:GetPlayers() do
			if v.Team ~= plr.Team and v.Character and v.Character.HumanoidRootPart and v.Character.Humanoid.Health > 0 and plrChams then
				chamPlr(v)
			end
		end
		while toggled == true do

			wait()
			local Player = game:GetService('Players').LocalPlayer
			Player.CharacterAdded:Wait()
			wait(5)
			for i,v in next,plrs:GetPlayers() do
				if v.Team ~= plr.Team and v.Character and v.Character.HumanoidRootPart and v.Character.Humanoid.Health > 0 and plrChams then
					chamPlr(v)
				end
			end
			plrs.ChildAdded:connect(function(v)
				v.CharacterAdded:connect(function(char)
					wait(3)
					if plrChams and plr.Team ~= v.Team and v.Character and v ~= plr then
						chamPlr(v)
					end
				end)
			end)
		end		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)

	end
end

button.Activated:Connect(onButtonActivated)

end))
TextLabel89.Name = "OuterChams"
TextLabel89.Parent = ImageButton87
TextLabel89.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel89.Size = UDim2.new(0, 324, 0, 20)
TextLabel89.BackgroundColor = BrickColor.new("Institutional white")
TextLabel89.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel89.BackgroundTransparency = 1
TextLabel89.Font = Enum.Font.SourceSans
TextLabel89.FontSize = Enum.FontSize.Size28
TextLabel89.Text = "Outer chams"
TextLabel89.TextColor = BrickColor.new("Institutional white")
TextLabel89.TextColor3 = Color3.new(1, 1, 1)
TextLabel89.TextSize = 26
TextLabel89.TextWrap = true
TextLabel89.TextWrapped = true
TextLabel89.TextXAlignment = Enum.TextXAlignment.Left
ImageButton90.Name = "Color"
ImageButton90.Parent = ImageButton87
ImageButton90.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton90.Size = UDim2.new(0, 40, 0, 14)
ImageButton90.BackgroundColor = BrickColor.new("Hot pink")
ImageButton90.BackgroundColor3 = Color3.new(1, 0.0941176, 0.882353)
ImageButton90.BorderColor = BrickColor.new("Really black")
ImageButton90.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton90.BorderSizePixel = 2
ImageButton90.Image = "rbxassetid://5761429802"
ImageButton90.ImageTransparency = 0.60000002384186
TextLabel91.Name = "Colored models"
TextLabel91.Parent = Frame86
TextLabel91.Position = UDim2.new(0.0361394361, 0, -0.041793488, 0)
TextLabel91.Size = UDim2.new(0, 173, 0, 11)
TextLabel91.Active = true
TextLabel91.BackgroundColor = BrickColor.new("Really black")
TextLabel91.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel91.BorderColor = BrickColor.new("Really black")
TextLabel91.BorderColor3 = Color3.new(0, 0, 0)
TextLabel91.BorderSizePixel = 0
TextLabel91.ZIndex = 2
TextLabel91.Font = Enum.Font.SourceSansBold
TextLabel91.FontSize = Enum.FontSize.Size28
TextLabel91.Text = "Colored models"
TextLabel91.TextColor = BrickColor.new("Mid gray")
TextLabel91.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel91.TextSize = 28
TextLabel91.TextWrap = true
TextLabel91.TextWrapped = true
ImageButton92.Name = "Chams"
ImageButton92.Parent = Frame86
ImageButton92.Position = UDim2.new(0.0919999927, 0, 0.0992320254, 0)
ImageButton92.Size = UDim2.new(0, 12, 0, 12)
ImageButton92.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton92.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton92.BorderColor = BrickColor.new("Really black")
ImageButton92.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton92.ZIndex = 999
ImageButton92.Image = "rbxassetid://5761429802"
ImageButton92.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton92.ImageTransparency = 0.25
LocalScript93.Name = "InnerChams"
LocalScript93.Parent = ImageButton92
table.insert(cors,sandbox(LocalScript93,function()
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local button = script.Parent
local toggled = false
local espFolder2 = Instance.new("Folder",game.CoreGui)
local Color = script.Parent.Color.BackgroundColor3


function chamPlr(plr)
	if plr.Character then
		for i,v in next,plr.Character:GetChildren() do
			if v:IsA("BasePart") and v.Name ~= "HumanoidRootPart" and v.Name ~= "Gun" then
				local chamThing = Instance.new("BoxHandleAdornment",espFolder2)
				chamThing.Size = v.Size
				chamThing.Transparency = 0.1
				chamThing.ZIndex = 2
				chamThing.AlwaysOnTop = true
				chamThing.Visible = true
				chamThing.Adornee = v
				chamThing.Color3 = Color
				plr.Character.HumanoidRootPart.AncestryChanged:connect(function()
				chamThing:Destroy()
				end)
			end
		end
	end
end



local function onButtonActivated()
	if toggled == false then
		toggled = true
		local plrChams = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		for i,v in next,plrs:GetPlayers() do
			if v.Team ~= plr.Team and v.Character and v.Character.HumanoidRootPart and v.Character.Humanoid.Health > 0 and plrChams then
				chamPlr(v)
			end
		end
		while toggled == true do
			
			wait()
			local Player = game:GetService('Players').LocalPlayer
			Player.CharacterAdded:Wait()
			wait(5)
			for i,v in next,plrs:GetPlayers() do
				if v.Team ~= plr.Team and v.Character and v.Character.HumanoidRootPart and v.Character.Humanoid.Health > 0 and plrChams then
					chamPlr(v)
				end
			end
			plrs.ChildAdded:connect(function(v)
				v.CharacterAdded:connect(function(char)
					wait(3)
					if plrChams and plr.Team ~= v.Team and v.Character and v ~= plr then
						chamPlr(v)
					end
				end)
			end)
		end		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
	end
end

button.Activated:Connect(onButtonActivated)

end))
TextLabel94.Name = "Chams"
TextLabel94.Parent = ImageButton92
TextLabel94.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel94.Size = UDim2.new(0, 324, 0, 20)
TextLabel94.BackgroundColor = BrickColor.new("Institutional white")
TextLabel94.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel94.BackgroundTransparency = 1
TextLabel94.Font = Enum.Font.SourceSans
TextLabel94.FontSize = Enum.FontSize.Size28
TextLabel94.Text = "Chams"
TextLabel94.TextColor = BrickColor.new("Institutional white")
TextLabel94.TextColor3 = Color3.new(1, 1, 1)
TextLabel94.TextSize = 26
TextLabel94.TextWrap = true
TextLabel94.TextWrapped = true
TextLabel94.TextXAlignment = Enum.TextXAlignment.Left
ImageButton95.Name = "Color"
ImageButton95.Parent = ImageButton92
ImageButton95.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton95.Size = UDim2.new(0, 40, 0, 14)
ImageButton95.BackgroundColor = BrickColor.new("Lilac")
ImageButton95.BackgroundColor3 = Color3.new(0.615686, 0.368627, 0.67451)
ImageButton95.BorderColor = BrickColor.new("Really black")
ImageButton95.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton95.BorderSizePixel = 2
ImageButton95.Image = "rbxassetid://5761429802"
ImageButton95.ImageColor3 = Color3.new(0.54902, 0.54902, 0.54902)
ImageButton95.ImageTransparency = 0.60000002384186
ImageButton96.Name = "Hands"
ImageButton96.Parent = Frame86
ImageButton96.Position = UDim2.new(0.0919999927, 0, 0.349887371, 0)
ImageButton96.Size = UDim2.new(0, 12, 0, 12)
ImageButton96.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton96.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton96.BorderColor = BrickColor.new("Really black")
ImageButton96.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton96.ZIndex = 999
ImageButton96.Image = "rbxassetid://5761429802"
ImageButton96.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton96.ImageTransparency = 0.25
TextLabel97.Name = "Hands"
TextLabel97.Parent = ImageButton96
TextLabel97.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel97.Size = UDim2.new(0, 324, 0, 20)
TextLabel97.BackgroundColor = BrickColor.new("Institutional white")
TextLabel97.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel97.BackgroundTransparency = 1
TextLabel97.Font = Enum.Font.SourceSans
TextLabel97.FontSize = Enum.FontSize.Size28
TextLabel97.Text = "Viewmodel material"
TextLabel97.TextColor = BrickColor.new("Institutional white")
TextLabel97.TextColor3 = Color3.new(1, 1, 1)
TextLabel97.TextSize = 26
TextLabel97.TextWrap = true
TextLabel97.TextWrapped = true
TextLabel97.TextXAlignment = Enum.TextXAlignment.Left
LocalScript98.Name = "Viewmodel"
LocalScript98.Parent = ImageButton96
table.insert(cors,sandbox(LocalScript98,function()
local button = script.Parent
local toggled = false
local TP = script.Parent.Parent.Parent.EffectsTab.ThirdPerson
local ArmColor = script.Parent.Color.BackgroundColor3
local GunColor = script.Parent.Color2.BackgroundColor3

function waste()
end
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		
		while toggled == true do
			if TP.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				wait()
				waste()
			else
				wait()
				if script.Parent.Parent.DropDown.Selection.Text == ("Forcefield") then
					for _,gun in pairs(workspace.Camera:GetDescendants()) do 
						if gun.Name ~= "Flash" and gun.Name ~= "Right Arm" and gun.Name ~= "Left Arm" and gun.Name ~= "Sleeve" and gun.Name ~= "Glove" then
							pcall(function() 
								gun.Material = Enum.Material.ForceField
								gun.Color = GunColor
								gun.Transparency = 0
							end)
						end				
					end
					for _,arm in pairs(workspace.Camera:GetDescendants()) do 
						if arm.Name ~= "Flash" and arm.Name ~= "Handle" and arm.Name ~= "Handle2" and arm.Name ~= "Mag" and arm.Name ~= "Mag2" and arm.Name ~= "Slide" and arm.Name ~= "Slide2" and arm.Name ~= "Barrel" and arm.Name ~= "Scope" and arm.Name ~= "Body" and arm.Name ~= "Part" then
							pcall(function() 
								arm.Material = Enum.Material.ForceField
								arm.Color = ArmColor
								arm.Transparency = 0.5
							end)
						end				
					end
					wait()
				end
			end	
		end				
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
end

		
end	
button.Activated:Connect(onButtonActivated)
end))
ImageButton99.Name = "Color"
ImageButton99.Parent = ImageButton96
ImageButton99.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton99.Size = UDim2.new(0, 40, 0, 14)
ImageButton99.BackgroundColor = BrickColor.new("Alder")
ImageButton99.BackgroundColor3 = Color3.new(0.690196, 0.309804, 1)
ImageButton99.BorderColor = BrickColor.new("Really black")
ImageButton99.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton99.BorderSizePixel = 2
ImageButton99.Image = "rbxassetid://5761429802"
ImageButton99.ImageTransparency = 0.60000002384186
ImageButton100.Name = "Color2"
ImageButton100.Parent = ImageButton96
ImageButton100.Position = UDim2.new(21.9493332, 0, -0.0829999968, 0)
ImageButton100.Size = UDim2.new(0, 40, 0, 14)
ImageButton100.BackgroundColor = BrickColor.new("Hot pink")
ImageButton100.BackgroundColor3 = Color3.new(1, 0.0627451, 0.831373)
ImageButton100.BorderColor = BrickColor.new("Really black")
ImageButton100.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton100.BorderSizePixel = 2
ImageButton100.Image = "rbxassetid://5761429802"
ImageButton100.ImageTransparency = 0.60000002384186
Frame101.Name = "DropDown2"
Frame101.Parent = Frame86
Frame101.Position = UDim2.new(0.194999993, 0, 1.0107007, 0)
Frame101.Size = UDim2.new(0.61330384, 0, 0.0452070087, 0)
Frame101.BackgroundColor = BrickColor.new("Really black")
Frame101.BackgroundColor3 = Color3.new(0, 0, 0)
Frame101.BackgroundTransparency = 1
Frame101.BorderSizePixel = 0
Frame101.ZIndex = 3
TextButton102.Name = "Selection"
TextButton102.Parent = Frame101
TextButton102.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton102.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton102.BackgroundColor = BrickColor.new("Black")
TextButton102.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton102.BorderColor = BrickColor.new("Dirt brown")
TextButton102.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton102.BorderSizePixel = 3
TextButton102.Font = Enum.Font.SourceSans
TextButton102.FontSize = Enum.FontSize.Size28
TextButton102.Text = "[...]"
TextButton102.TextColor = BrickColor.new("Institutional white")
TextButton102.TextColor3 = Color3.new(1, 1, 1)
TextButton102.TextSize = 26
TextButton102.TextWrap = true
TextButton102.TextWrapped = true
Frame103.Name = "Menu"
Frame103.Parent = Frame101
Frame103.Position = UDim2.new(0, 0, -5.02099991, 3)
Frame103.Visible = false
Frame103.Size = UDim2.new(1, 0, 8.36900043, 0)
Frame103.BackgroundColor = BrickColor.new("Black")
Frame103.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame103.BorderColor = BrickColor.new("Dirt brown")
Frame103.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame103.BorderSizePixel = 3
Frame103.ZIndex = 4
TextButton104.Name = "Button"
TextButton104.Parent = Frame103
TextButton104.Size = UDim2.new(1, 0, -0.0132636894, 35)
TextButton104.BackgroundColor = BrickColor.new("Black metallic")
TextButton104.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton104.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton104.BorderSizePixel = 0
TextButton104.ZIndex = 4
TextButton104.Font = Enum.Font.SourceSans
TextButton104.FontSize = Enum.FontSize.Size28
TextButton104.Text = "Neon"
TextButton104.TextColor = BrickColor.new("Institutional white")
TextButton104.TextColor3 = Color3.new(1, 1, 1)
TextButton104.TextSize = 26
TextButton104.TextWrap = true
TextButton104.TextWrapped = true
TextButton105.Name = "Button2"
TextButton105.Parent = Frame103
TextButton105.Position = UDim2.new(0, 0, 0.324363798, 0)
TextButton105.Size = UDim2.new(1, 0, 0.000518417335, 35)
TextButton105.BackgroundColor = BrickColor.new("Black metallic")
TextButton105.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton105.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton105.BorderSizePixel = 0
TextButton105.ZIndex = 4
TextButton105.Font = Enum.Font.SourceSans
TextButton105.FontSize = Enum.FontSize.Size28
TextButton105.Text = "Forcefield"
TextButton105.TextColor = BrickColor.new("Institutional white")
TextButton105.TextColor3 = Color3.new(1, 1, 1)
TextButton105.TextSize = 26
TextButton105.TextWrap = true
TextButton105.TextWrapped = true
TextButton106.Name = "Button3"
TextButton106.Parent = Frame103
TextButton106.Position = UDim2.new(-0.00384554989, 0, 0.66185379, 0)
TextButton106.Size = UDim2.new(1, 0, 0.000518417335, 35)
TextButton106.BackgroundColor = BrickColor.new("Black metallic")
TextButton106.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton106.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton106.BorderSizePixel = 0
TextButton106.ZIndex = 4
TextButton106.Font = Enum.Font.SourceSans
TextButton106.FontSize = Enum.FontSize.Size28
TextButton106.Text = "Plastic"
TextButton106.TextColor = BrickColor.new("Institutional white")
TextButton106.TextColor3 = Color3.new(1, 1, 1)
TextButton106.TextSize = 26
TextButton106.TextWrap = true
TextButton106.TextWrapped = true
LocalScript107.Name = "Effect"
LocalScript107.Parent = Frame101
table.insert(cors,sandbox(LocalScript107,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
ImageButton108.Name = "LocalMaterial"
ImageButton108.Parent = Frame86
ImageButton108.Position = UDim2.new(0.0919999927, 0, 0.598062575, 0)
ImageButton108.Size = UDim2.new(0, 12, 0, 12)
ImageButton108.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton108.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton108.BorderColor = BrickColor.new("Really black")
ImageButton108.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton108.ZIndex = 999
ImageButton108.Image = "rbxassetid://5761429802"
ImageButton108.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton108.ImageTransparency = 0.25
TextLabel109.Name = "Hands"
TextLabel109.Parent = ImageButton108
TextLabel109.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel109.Size = UDim2.new(0, 324, 0, 20)
TextLabel109.BackgroundColor = BrickColor.new("Institutional white")
TextLabel109.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel109.BackgroundTransparency = 1
TextLabel109.Font = Enum.Font.SourceSans
TextLabel109.FontSize = Enum.FontSize.Size28
TextLabel109.Text = "Local material"
TextLabel109.TextColor = BrickColor.new("Institutional white")
TextLabel109.TextColor3 = Color3.new(1, 1, 1)
TextLabel109.TextSize = 26
TextLabel109.TextWrap = true
TextLabel109.TextWrapped = true
TextLabel109.TextXAlignment = Enum.TextXAlignment.Left
LocalScript110.Name = "LocalMaterial"
LocalScript110.Parent = ImageButton108
table.insert(cors,sandbox(LocalScript110,function()
local button = script.Parent
local toggled = false
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		while toggled == true do
			wait(1/100)
			if plr.Character then
				if script.Parent.Parent.DropDown2.Selection.Text == ("Plastic") then
					for _,v in pairs(workspace.yourself:GetDescendants()) do 
						if v:IsA("Part") or v:IsA("MeshPart") then
							pcall(function() 
								v.Material = Enum.Material.Plastic
								v.BrickColor = BrickColor.new("White")
								v.Transparency = 0
							end)
						end
					end
				end

				if script.Parent.Parent.DropDown2.Selection.Text == ("Forcefield") then
					for _,v in pairs(plrs.LocalPlayer.Character:GetDescendants()) do 
						if v:IsA("Part") or v:IsA("MeshPart") then
							pcall(function() 
								v.Material = Enum.Material.ForceField
								v.BrickColor = BrickColor.new("White")
								v.Transparency = 0.1
							end)
						end
					end
				end

				if script.Parent.Parent.DropDown2.Selection.Text == ("Neon") then
					for _,v in pairs(workspace.yourself:GetDescendants()) do 
						if v:IsA("Part") or v:IsA("MeshPart") then
							pcall(function() 
								v.Material = Enum.Material.Neon
								v.BrickColor = BrickColor.new("White")
								v.Transparency = 0
							end)
						end
					end
				end
			end
		end	
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
end

		
end	
button.Activated:Connect(onButtonActivated)
end))
ImageButton111.Name = "Color"
ImageButton111.Parent = ImageButton108
ImageButton111.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton111.Size = UDim2.new(0, 40, 0, 14)
ImageButton111.BackgroundColor = BrickColor.new("Institutional white")
ImageButton111.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton111.BorderColor = BrickColor.new("Really black")
ImageButton111.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton111.BorderSizePixel = 2
ImageButton111.Image = "rbxassetid://5761429802"
ImageButton111.ImageTransparency = 0.60000002384186
Frame112.Name = "DropDown"
Frame112.Parent = Frame86
Frame112.Position = UDim2.new(0.194999993, 0, 0.762525558, 0)
Frame112.Size = UDim2.new(0.61330384, 0, 0.0452070087, 0)
Frame112.BackgroundColor = BrickColor.new("Really black")
Frame112.BackgroundColor3 = Color3.new(0, 0, 0)
Frame112.BackgroundTransparency = 1
Frame112.BorderSizePixel = 0
Frame112.ZIndex = 3
TextButton113.Name = "Selection"
TextButton113.Parent = Frame112
TextButton113.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton113.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton113.BackgroundColor = BrickColor.new("Black")
TextButton113.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton113.BorderColor = BrickColor.new("Dirt brown")
TextButton113.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton113.BorderSizePixel = 3
TextButton113.Font = Enum.Font.SourceSans
TextButton113.FontSize = Enum.FontSize.Size28
TextButton113.Text = "[...]"
TextButton113.TextColor = BrickColor.new("Institutional white")
TextButton113.TextColor3 = Color3.new(1, 1, 1)
TextButton113.TextSize = 26
TextButton113.TextWrap = true
TextButton113.TextWrapped = true
Frame114.Name = "Menu"
Frame114.Parent = Frame112
Frame114.Position = UDim2.new(0, 0, -5.02099991, 3)
Frame114.Visible = false
Frame114.Size = UDim2.new(1, 0, 8.36900043, 0)
Frame114.BackgroundColor = BrickColor.new("Black")
Frame114.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame114.BorderColor = BrickColor.new("Dirt brown")
Frame114.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame114.BorderSizePixel = 3
Frame114.ZIndex = 4
TextButton115.Name = "Button"
TextButton115.Parent = Frame114
TextButton115.Size = UDim2.new(1, 0, -0.0132636894, 35)
TextButton115.BackgroundColor = BrickColor.new("Black metallic")
TextButton115.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton115.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton115.BorderSizePixel = 0
TextButton115.ZIndex = 4
TextButton115.Font = Enum.Font.SourceSans
TextButton115.FontSize = Enum.FontSize.Size28
TextButton115.Text = "Neon"
TextButton115.TextColor = BrickColor.new("Institutional white")
TextButton115.TextColor3 = Color3.new(1, 1, 1)
TextButton115.TextSize = 26
TextButton115.TextWrap = true
TextButton115.TextWrapped = true
TextButton116.Name = "Button2"
TextButton116.Parent = Frame114
TextButton116.Position = UDim2.new(0, 0, 0.324363798, 0)
TextButton116.Size = UDim2.new(1, 0, 0.000518417335, 35)
TextButton116.BackgroundColor = BrickColor.new("Black metallic")
TextButton116.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton116.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton116.BorderSizePixel = 0
TextButton116.ZIndex = 4
TextButton116.Font = Enum.Font.SourceSans
TextButton116.FontSize = Enum.FontSize.Size28
TextButton116.Text = "Forcefield"
TextButton116.TextColor = BrickColor.new("Institutional white")
TextButton116.TextColor3 = Color3.new(1, 1, 1)
TextButton116.TextSize = 26
TextButton116.TextWrap = true
TextButton116.TextWrapped = true
TextButton117.Name = "Button3"
TextButton117.Parent = Frame114
TextButton117.Position = UDim2.new(-0.00384554989, 0, 0.66185379, 0)
TextButton117.Size = UDim2.new(1, 0, 0.000518417335, 35)
TextButton117.BackgroundColor = BrickColor.new("Black metallic")
TextButton117.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton117.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton117.BorderSizePixel = 0
TextButton117.ZIndex = 4
TextButton117.Font = Enum.Font.SourceSans
TextButton117.FontSize = Enum.FontSize.Size28
TextButton117.Text = "Plastic"
TextButton117.TextColor = BrickColor.new("Institutional white")
TextButton117.TextColor3 = Color3.new(1, 1, 1)
TextButton117.TextSize = 26
TextButton117.TextWrap = true
TextButton117.TextWrapped = true
LocalScript118.Name = "Effect"
LocalScript118.Parent = Frame112
table.insert(cors,sandbox(LocalScript118,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
Frame119.Name = "EffectsTab"
Frame119.Parent = Frame85
Frame119.Position = UDim2.new(0.526000082, 0, 0.403601199, 0)
Frame119.Size = UDim2.new(0, 424, 0, 584)
Frame119.BackgroundColor = BrickColor.new("Really black")
Frame119.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame119.BorderColor = BrickColor.new("Dirt brown")
Frame119.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame119.BorderSizePixel = 2
Frame120.Name = "DropDown2"
Frame120.Parent = Frame119
Frame120.Position = UDim2.new(0.193000004, 0, 0.859000027, 0)
Frame120.Size = UDim2.new(0.61330384, 0, 0.021850165, 0)
Frame120.BackgroundColor = BrickColor.new("Institutional white")
Frame120.BackgroundColor3 = Color3.new(1, 1, 1)
Frame120.BackgroundTransparency = 1
Frame120.BorderSizePixel = 0
Frame120.ZIndex = 3
TextButton121.Name = "Selection"
TextButton121.Parent = Frame120
TextButton121.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton121.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton121.BackgroundColor = BrickColor.new("Black")
TextButton121.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton121.BorderColor = BrickColor.new("Dirt brown")
TextButton121.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton121.BorderSizePixel = 3
TextButton121.Font = Enum.Font.SourceSans
TextButton121.FontSize = Enum.FontSize.Size28
TextButton121.Text = "[...]"
TextButton121.TextColor = BrickColor.new("Institutional white")
TextButton121.TextColor3 = Color3.new(1, 1, 1)
TextButton121.TextSize = 26
TextButton121.TextWrap = true
TextButton121.TextWrapped = true
Frame122.Name = "Menu"
Frame122.Parent = Frame120
Frame122.Position = UDim2.new(0, 0, -5.02099848, 3)
Frame122.Visible = false
Frame122.Size = UDim2.new(1, 0, 15.9816628, 0)
Frame122.BackgroundColor = BrickColor.new("Black")
Frame122.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame122.BorderColor = BrickColor.new("Dirt brown")
Frame122.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame122.BorderSizePixel = 3
Frame122.ZIndex = 10
TextButton123.Name = "Button6"
TextButton123.Parent = Frame122
TextButton123.Position = UDim2.new(-6.98491931e-10, 0, 0.848056555, 0)
TextButton123.Size = UDim2.new(1, 0, -0.00380410277, 35)
TextButton123.BackgroundColor = BrickColor.new("Black metallic")
TextButton123.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton123.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton123.BorderSizePixel = 0
TextButton123.ZIndex = 10
TextButton123.Font = Enum.Font.SourceSans
TextButton123.FontSize = Enum.FontSize.Size28
TextButton123.Text = "Twighlight"
TextButton123.TextColor = BrickColor.new("Institutional white")
TextButton123.TextColor3 = Color3.new(1, 1, 1)
TextButton123.TextSize = 26
TextButton123.TextWrap = true
TextButton123.TextWrapped = true
TextButton124.Name = "Button5"
TextButton124.Parent = Frame122
TextButton124.Position = UDim2.new(0, 0, 0.676689744, 0)
TextButton124.Size = UDim2.new(1, 0, 0, 35)
TextButton124.BackgroundColor = BrickColor.new("Black metallic")
TextButton124.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton124.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton124.BorderSizePixel = 0
TextButton124.ZIndex = 10
TextButton124.Font = Enum.Font.SourceSans
TextButton124.FontSize = Enum.FontSize.Size28
TextButton124.Text = "Vivid Skies"
TextButton124.TextColor = BrickColor.new("Institutional white")
TextButton124.TextColor3 = Color3.new(1, 1, 1)
TextButton124.TextSize = 26
TextButton124.TextWrap = true
TextButton124.TextWrapped = true
TextButton125.Name = "Button4"
TextButton125.Parent = Frame122
TextButton125.Position = UDim2.new(-6.98491931e-10, 0, 0.509711742, 0)
TextButton125.Size = UDim2.new(1, 0, -0.00380410277, 35)
TextButton125.BackgroundColor = BrickColor.new("Black metallic")
TextButton125.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton125.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton125.BorderSizePixel = 0
TextButton125.ZIndex = 10
TextButton125.Font = Enum.Font.SourceSans
TextButton125.FontSize = Enum.FontSize.Size28
TextButton125.Text = "Dark Blue"
TextButton125.TextColor = BrickColor.new("Institutional white")
TextButton125.TextColor3 = Color3.new(1, 1, 1)
TextButton125.TextSize = 26
TextButton125.TextWrap = true
TextButton125.TextWrapped = true
TextButton126.Name = "Button3"
TextButton126.Parent = Frame122
TextButton126.Position = UDim2.new(0, 0, 0.338344872, 0)
TextButton126.Size = UDim2.new(1, 0, 0, 35)
TextButton126.BackgroundColor = BrickColor.new("Black metallic")
TextButton126.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton126.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton126.BorderSizePixel = 0
TextButton126.ZIndex = 10
TextButton126.Font = Enum.Font.SourceSans
TextButton126.FontSize = Enum.FontSize.Size28
TextButton126.Text = "Purple Nebula"
TextButton126.TextColor = BrickColor.new("Institutional white")
TextButton126.TextColor3 = Color3.new(1, 1, 1)
TextButton126.TextSize = 26
TextButton126.TextWrap = true
TextButton126.TextWrapped = true
TextButton127.Name = "Button"
TextButton127.Parent = Frame122
TextButton127.Size = UDim2.new(1, 0, 0, 35)
TextButton127.BackgroundColor = BrickColor.new("Black metallic")
TextButton127.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton127.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton127.BorderSizePixel = 0
TextButton127.ZIndex = 10
TextButton127.Font = Enum.Font.SourceSans
TextButton127.FontSize = Enum.FontSize.Size28
TextButton127.Text = "Purple Clouds"
TextButton127.TextColor = BrickColor.new("Institutional white")
TextButton127.TextColor3 = Color3.new(1, 1, 1)
TextButton127.TextSize = 26
TextButton127.TextWrap = true
TextButton127.TextWrapped = true
TextButton128.Name = "Button2"
TextButton128.Parent = Frame122
TextButton128.Position = UDim2.new(-2.32830644e-10, 0, 0.1713669, 0)
TextButton128.Size = UDim2.new(1, 0, -0.00380410277, 35)
TextButton128.BackgroundColor = BrickColor.new("Black metallic")
TextButton128.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton128.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton128.BorderSizePixel = 0
TextButton128.ZIndex = 10
TextButton128.Font = Enum.Font.SourceSans
TextButton128.FontSize = Enum.FontSize.Size28
TextButton128.Text = "Cloudy Skies"
TextButton128.TextColor = BrickColor.new("Institutional white")
TextButton128.TextColor3 = Color3.new(1, 1, 1)
TextButton128.TextSize = 26
TextButton128.TextWrap = true
TextButton128.TextWrapped = true
LocalScript129.Name = "Effect"
LocalScript129.Parent = Frame120
table.insert(cors,sandbox(LocalScript129,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
ImageButton130.Name = "Ambience"
ImageButton130.Parent = Frame119
ImageButton130.Position = UDim2.new(0.0920001343, 0, 0.601786792, 0)
ImageButton130.Size = UDim2.new(0, 12, 0, 11)
ImageButton130.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton130.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton130.BorderColor = BrickColor.new("Really black")
ImageButton130.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton130.ZIndex = 999
ImageButton130.Image = "rbxassetid://5761429802"
ImageButton130.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton130.ImageTransparency = 0.25
TextLabel131.Name = "Ambience"
TextLabel131.Parent = ImageButton130
TextLabel131.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel131.Size = UDim2.new(0, 324, 0, 20)
TextLabel131.BackgroundColor = BrickColor.new("Institutional white")
TextLabel131.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel131.BackgroundTransparency = 1
TextLabel131.Font = Enum.Font.SourceSans
TextLabel131.FontSize = Enum.FontSize.Size28
TextLabel131.Text = "Ambient color"
TextLabel131.TextColor = BrickColor.new("Institutional white")
TextLabel131.TextColor3 = Color3.new(1, 1, 1)
TextLabel131.TextSize = 26
TextLabel131.TextWrap = true
TextLabel131.TextWrapped = true
TextLabel131.TextXAlignment = Enum.TextXAlignment.Left
LocalScript132.Name = "Ambience"
LocalScript132.Parent = ImageButton130
table.insert(cors,sandbox(LocalScript132,function()
local button = script.Parent
local toggled = false
local Color = script.Parent.Color.BackgroundColor3
local lighting = game.Lighting

function DeleteFX()
	if toggled == false then
		lighting.ColorShift_Top = Color3.fromRGB(255, 255, 255)
		local returnTable = {}
		for i,v in pairs (lighting:GetChildren()) do
			if v:IsA("ColorCorrectionEffect") then
				if v.Name == "Ambience" then
					v:Destroy()			
				end	
			end
		end
	end	
end

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		
		Instance.new("ColorCorrectionEffect", game.Lighting)
		local ColorCorrection = game.Lighting.ColorCorrection
		ColorCorrection.Name = "Ambience"
		ColorCorrection.TintColor = Color
		lighting.ColorShift_Top = Color
	
			
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		DeleteFX()
	end
end

button.Activated:Connect(onButtonActivated)


end))
ImageButton133.Name = "Color"
ImageButton133.Parent = ImageButton130
ImageButton133.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton133.Size = UDim2.new(0, 40, 0, 14)
ImageButton133.BackgroundColor = BrickColor.new("Bright reddish lilac")
ImageButton133.BackgroundColor3 = Color3.new(0.584314, 0.294118, 0.568627)
ImageButton133.BorderColor = BrickColor.new("Really black")
ImageButton133.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton133.BorderSizePixel = 2
ImageButton133.Image = "rbxassetid://5761429802"
ImageButton133.ImageColor3 = Color3.new(0.984314, 0.709804, 1)
ImageButton133.ImageTransparency = 0.60000002384186
ImageButton134.Name = "NoSky"
ImageButton134.Parent = Frame119
ImageButton134.Position = UDim2.new(0.0920000002, 0, 0.662, 0)
ImageButton134.Size = UDim2.new(0, 12, 0, 11)
ImageButton134.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton134.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton134.BorderColor = BrickColor.new("Really black")
ImageButton134.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton134.ZIndex = 999
ImageButton134.Image = "rbxassetid://5761429802"
ImageButton134.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton134.ImageTransparency = 0.25
TextLabel135.Name = "NoSky"
TextLabel135.Parent = ImageButton134
TextLabel135.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel135.Size = UDim2.new(0, 324, 0, 20)
TextLabel135.BackgroundColor = BrickColor.new("Institutional white")
TextLabel135.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel135.BackgroundTransparency = 1
TextLabel135.Font = Enum.Font.SourceSans
TextLabel135.FontSize = Enum.FontSize.Size28
TextLabel135.Text = "Skybox effects"
TextLabel135.TextColor = BrickColor.new("Institutional white")
TextLabel135.TextColor3 = Color3.new(1, 1, 1)
TextLabel135.TextSize = 26
TextLabel135.TextWrap = true
TextLabel135.TextWrapped = true
TextLabel135.TextXAlignment = Enum.TextXAlignment.Left
LocalScript136.Name = "Function"
LocalScript136.Parent = ImageButton134
table.insert(cors,sandbox(LocalScript136,function()
local button = script.Parent
local toggled = false


local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)

		local Sky = Instance.new("Sky")
		Sky.Parent = game.Lighting
		Sky.Name = "Sky"

		
		while wait() do
			if toggled == true then
				if script.Parent.Parent.DropDown2.Selection.Text == "Purple Clouds" then
					--Purple Clouds
					Sky.SkyboxLf = "rbxassetid://570557620"
					Sky.SkyboxBk = "rbxassetid://570557514"
					Sky.SkyboxDn = "rbxassetid://570557775"
					Sky.SkyboxFt = "rbxassetid://570557559"
					Sky.SkyboxRt = "rbxassetid://570557672"
					Sky.SkyboxUp = "rbxassetid://570557727"
				end
				if script.Parent.Parent.DropDown2.Selection.Text == "Cloudy Skies" then
					--Cloudy Skies
					Sky.SkyboxLf = "rbxassetid://252760980"
					Sky.SkyboxBk = "rbxassetid://252760981"
					Sky.SkyboxDn = "rbxassetid://252763035"
					Sky.SkyboxFt = "rbxassetid://252761439"
					Sky.SkyboxRt = "rbxassetid://252760986"
					Sky.SkyboxUp = "rbxassetid://252762652"
				end
				if script.Parent.Parent.DropDown2.Selection.Text == "Purple Nebula" then
					--Purple Nebula
					Sky.SkyboxLf = "rbxassetid://159454286"
					Sky.SkyboxBk = "rbxassetid://159454299"
					Sky.SkyboxDn = "rbxassetid://159454296"
					Sky.SkyboxFt = "rbxassetid://159454293"
					Sky.SkyboxRt = "rbxassetid://159454300"
					Sky.SkyboxUp = "rbxassetid://159454288"
				end
				if script.Parent.Parent.DropDown2.Selection.Text == "Dark Blue" then
					--Dark blue
					Sky.SkyboxLf = "rbxassetid://30306626"
					Sky.SkyboxBk = "rbxassetid://30306692"
					Sky.SkyboxDn = "rbxassetid://25901058"
					Sky.SkyboxFt = "rbxassetid://30306730"
					Sky.SkyboxRt = "rbxassetid://30306661"
					Sky.SkyboxUp = "rbxassetid://30306770"
				end
				if script.Parent.Parent.DropDown2.Selection.Text == "Vivid Skies" then
					--Vivid Skies
					Sky.SkyboxLf = "rbxassetid://271042310"
					Sky.SkyboxBk = "rbxassetid://271042516"
					Sky.SkyboxDn = "rbxassetid://271077243"
					Sky.SkyboxFt = "rbxassetid://271042556"
					Sky.SkyboxRt = "rbxassetid://271042467"
					Sky.SkyboxUp = "rbxassetid://271077958"
				end
				if script.Parent.Parent.DropDown2.Selection.Text == "Twighlight" then
					--Twighlight
					Sky.SkyboxLf = "rbxassetid://264909758"
					Sky.SkyboxBk = "rbxassetid://264908339"
					Sky.SkyboxDn = "rbxassetid://264907909"
					Sky.SkyboxFt = "rbxassetid://264909420"
					Sky.SkyboxRt = "rbxassetid://264908886"
					Sky.SkyboxUp = "rbxassetid://264907379"
				end
			end
		end
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Lighting.Sky:Destroy()
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton137.Name = "Asus"
ImageButton137.Parent = Frame119
ImageButton137.Position = UDim2.new(0.0920001343, 0, 0.49048543, 0)
ImageButton137.Size = UDim2.new(0, 12, 0, 11)
ImageButton137.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton137.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton137.BorderColor = BrickColor.new("Really black")
ImageButton137.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton137.ZIndex = 999
ImageButton137.Image = "rbxassetid://5761429802"
ImageButton137.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton137.ImageTransparency = 0.25
LocalScript138.Name = "AsusWalls"
LocalScript138.Parent = ImageButton137
table.insert(cors,sandbox(LocalScript138,function()
local button = script.Parent
local toggled = false

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		for i,p in pairs(workspace.Map.Geometry:GetDescendants()) do
			if p:IsA("Part") then
				if script.Parent.Trans.Text ~= "" then
					p.Transparency = script.Parent.Trans.Text
				end
			end
		end


		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for i,p in pairs(workspace.Map:GetDescendants()) do
			if p:IsA("Part") then
				p.Transparency = 0
			end
		end
	end
end

button.Activated:Connect(onButtonActivated)
end))
TextBox139.Name = "Trans"
TextBox139.Parent = ImageButton137
TextBox139.Position = UDim2.new(3.56866455, 0, 1.92391133, 0)
TextBox139.Size = UDim2.new(0, 259, 0, 27)
TextBox139.BackgroundColor = BrickColor.new("Black")
TextBox139.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextBox139.BorderColor = BrickColor.new("Dirt brown")
TextBox139.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextBox139.BorderSizePixel = 3
TextBox139.Font = Enum.Font.SourceSans
TextBox139.FontSize = Enum.FontSize.Size28
TextBox139.Text = ""
TextBox139.TextColor = BrickColor.new("Institutional white")
TextBox139.TextColor3 = Color3.new(1, 1, 1)
TextBox139.TextSize = 26
TextBox139.ClearTextOnFocus = false
TextBox139.PlaceholderColor3 = Color3.new(1, 1, 1)
TextBox139.PlaceholderText = "Transparency"
TextLabel140.Name = "Asus"
TextLabel140.Parent = ImageButton137
TextLabel140.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel140.Size = UDim2.new(0, 324, 0, 20)
TextLabel140.BackgroundColor = BrickColor.new("Institutional white")
TextLabel140.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel140.BackgroundTransparency = 1
TextLabel140.Font = Enum.Font.SourceSans
TextLabel140.FontSize = Enum.FontSize.Size28
TextLabel140.Text = "Transparent props"
TextLabel140.TextColor = BrickColor.new("Institutional white")
TextLabel140.TextColor3 = Color3.new(1, 1, 1)
TextLabel140.TextSize = 26
TextLabel140.TextWrap = true
TextLabel140.TextWrapped = true
TextLabel140.TextXAlignment = Enum.TextXAlignment.Left
TextLabel141.Name = "Effects"
TextLabel141.Parent = Frame119
TextLabel141.Position = UDim2.new(0.0361394361, 0, -0.0159183666, 0)
TextLabel141.Size = UDim2.new(0, 75, 0, 10)
TextLabel141.Active = true
TextLabel141.BackgroundColor = BrickColor.new("Really black")
TextLabel141.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel141.BorderColor = BrickColor.new("Really black")
TextLabel141.BorderColor3 = Color3.new(0, 0, 0)
TextLabel141.BorderSizePixel = 0
TextLabel141.ZIndex = 2
TextLabel141.Font = Enum.Font.SourceSansBold
TextLabel141.FontSize = Enum.FontSize.Size28
TextLabel141.Text = "Effects"
TextLabel141.TextColor = BrickColor.new("Mid gray")
TextLabel141.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel141.TextSize = 28
TextLabel141.TextWrap = true
TextLabel141.TextWrapped = true
ImageButton142.Name = "NoFlash"
ImageButton142.Parent = Frame119
ImageButton142.Position = UDim2.new(0.0920001343, 0, 0.0576301478, 0)
ImageButton142.Size = UDim2.new(0, 12, 0, 11)
ImageButton142.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton142.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton142.BorderColor = BrickColor.new("Really black")
ImageButton142.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton142.ZIndex = 999
ImageButton142.Image = "rbxassetid://5761429802"
ImageButton142.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton142.ImageTransparency = 0.25
TextLabel143.Name = "Remove flashbang effects"
TextLabel143.Parent = ImageButton142
TextLabel143.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel143.Size = UDim2.new(0, 324, 0, 20)
TextLabel143.BackgroundColor = BrickColor.new("Institutional white")
TextLabel143.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel143.BackgroundTransparency = 1
TextLabel143.Font = Enum.Font.SourceSans
TextLabel143.FontSize = Enum.FontSize.Size28
TextLabel143.Text = "Remove flashbang effects"
TextLabel143.TextColor = BrickColor.new("Institutional white")
TextLabel143.TextColor3 = Color3.new(1, 1, 1)
TextLabel143.TextSize = 26
TextLabel143.TextWrap = true
TextLabel143.TextWrapped = true
TextLabel143.TextXAlignment = Enum.TextXAlignment.Left
LocalScript144.Name = "NoFlash"
LocalScript144.Parent = ImageButton142
table.insert(cors,sandbox(LocalScript144,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		while toggled == true do
			wait()
			game.Players.LocalPlayer.PlayerGui.Blnd.Blind.Visible=false
		end
		
		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		while toggled == true do
			wait()
			game.Players.LocalPlayer.PlayerGui.Blnd.Blind.Visible=true
			end		
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton145.Name = "NoSmoke"
ImageButton145.Parent = Frame119
ImageButton145.Position = UDim2.new(0.0920001343, 0, 0.118526511, 0)
ImageButton145.Size = UDim2.new(0, 12, 0, 11)
ImageButton145.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton145.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton145.BorderColor = BrickColor.new("Really black")
ImageButton145.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton145.ZIndex = 999
ImageButton145.Image = "rbxassetid://5761429802"
ImageButton145.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton145.ImageTransparency = 0.25
TextLabel146.Name = "Remove smoke gernades"
TextLabel146.Parent = ImageButton145
TextLabel146.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel146.Size = UDim2.new(0, 324, 0, 20)
TextLabel146.BackgroundColor = BrickColor.new("Institutional white")
TextLabel146.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel146.BackgroundTransparency = 1
TextLabel146.Font = Enum.Font.SourceSans
TextLabel146.FontSize = Enum.FontSize.Size28
TextLabel146.Text = "Remove smoke effects"
TextLabel146.TextColor = BrickColor.new("Institutional white")
TextLabel146.TextColor3 = Color3.new(1, 1, 1)
TextLabel146.TextSize = 26
TextLabel146.TextWrap = true
TextLabel146.TextWrapped = true
TextLabel146.TextXAlignment = Enum.TextXAlignment.Left
LocalScript147.Name = "NoSmoke"
LocalScript147.Parent = ImageButton145
table.insert(cors,sandbox(LocalScript147,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		while toggled == true do
			spawn(function()
				workspace:WaitForChild("Ray_Ignore"):WaitForChild("Smokes").DescendantAdded:connect(function(v)
					if toggled then
						v:Remove()
					end
					if toggled then
						if v:IsA("ParticleEmitter") then 
							v.Texture = "rbxassetid://65437818"
							v.Size = NumberSequence.new(0,3)
							v.Transparency = NumberSequence.new(0.9)
							v.SpreadAngle = Vector2.new(0, 0)
							v.Rate = 0.001
							v.Acceleration = Vector3.new(0,0,0)
							v.Lifetime = NumberRange.new(0, 4)
							v.Speed = NumberRange.new(0, 0)
							v.RotSpeed = NumberRange.new(-20, 20)
							v.Rotation = NumberRange.new(-90, 90)
						end		
						if v:IsA("Part") then
							v.Transparency = 1
						end
					end
				end)
			end)
			wait()
		end	
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)			
	end
end

button.Activated:Connect(onButtonActivated)



end))
ImageButton148.Name = "NoFog"
ImageButton148.Parent = Frame119
ImageButton148.Position = UDim2.new(0.0920001343, 0, 0.178336054, 0)
ImageButton148.Size = UDim2.new(0, 12, 0, 11)
ImageButton148.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton148.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton148.BorderColor = BrickColor.new("Really black")
ImageButton148.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton148.ZIndex = 999
ImageButton148.Image = "rbxassetid://5761429802"
ImageButton148.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton148.ImageTransparency = 0.25
TextLabel149.Name = "Remove fog"
TextLabel149.Parent = ImageButton148
TextLabel149.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel149.Size = UDim2.new(0, 324, 0, 20)
TextLabel149.BackgroundColor = BrickColor.new("Institutional white")
TextLabel149.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel149.BackgroundTransparency = 1
TextLabel149.Font = Enum.Font.SourceSans
TextLabel149.FontSize = Enum.FontSize.Size28
TextLabel149.Text = "Fog effects"
TextLabel149.TextColor = BrickColor.new("Institutional white")
TextLabel149.TextColor3 = Color3.new(1, 1, 1)
TextLabel149.TextSize = 26
TextLabel149.TextWrap = true
TextLabel149.TextWrapped = true
TextLabel149.TextXAlignment = Enum.TextXAlignment.Left
LocalScript150.Name = "Function"
LocalScript150.Parent = ImageButton148
table.insert(cors,sandbox(LocalScript150,function()
local button = script.Parent
local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		
		game.Lighting.FogStart = 0
		game.Lighting.FogEnd = 300
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
		game.Lighting.FogStart = 99999999999999
		game.Lighting.FogEnd = 999999999999
		
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton151.Name = "NoScope"
ImageButton151.Parent = Frame119
ImageButton151.Position = UDim2.new(0.0920001343, 0, 0.238520369, 0)
ImageButton151.Size = UDim2.new(0, 12, 0, 11)
ImageButton151.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton151.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton151.BorderColor = BrickColor.new("Really black")
ImageButton151.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton151.ZIndex = 999
ImageButton151.Image = "rbxassetid://5761429802"
ImageButton151.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton151.ImageTransparency = 0.25
TextLabel152.Parent = ImageButton151
TextLabel152.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel152.Size = UDim2.new(0, 324, 0, 20)
TextLabel152.BackgroundColor = BrickColor.new("Institutional white")
TextLabel152.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel152.BackgroundTransparency = 1
TextLabel152.Font = Enum.Font.SourceSans
TextLabel152.FontSize = Enum.FontSize.Size28
TextLabel152.Text = "Remove scope overlay"
TextLabel152.TextColor = BrickColor.new("Institutional white")
TextLabel152.TextColor3 = Color3.new(1, 1, 1)
TextLabel152.TextSize = 26
TextLabel152.TextWrap = true
TextLabel152.TextWrapped = true
TextLabel152.TextXAlignment = Enum.TextXAlignment.Left
LocalScript153.Name = "Function"
LocalScript153.Parent = ImageButton151
table.insert(cors,sandbox(LocalScript153,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		
		while toggled == true do
		wait()	
			game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Scope.ImageTransparency = 1
			game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame4.BackgroundTransparency = 1
			game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame3.BackgroundTransparency = 1
			game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame2.BackgroundTransparency = 1
			game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame1.BackgroundTransparency = 1

		end
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		while toggled == false do
		wait()
		game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Scope.ImageTransparency = 0
		game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame4.BackgroundTransparency = 0
		game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame3.BackgroundTransparency = 0
		game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame2.BackgroundTransparency = 0
		game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Frame1.BackgroundTransparency = 0
		end
		
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton154.Name = "ThirdPerson"
ImageButton154.Parent = Frame119
ImageButton154.Position = UDim2.new(0.0920001343, 0, 0.298704594, 0)
ImageButton154.Size = UDim2.new(0, 12, 0, 11)
ImageButton154.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton154.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton154.BorderColor = BrickColor.new("Really black")
ImageButton154.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton154.ZIndex = 999
ImageButton154.Image = "rbxassetid://5761429802"
ImageButton154.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton154.ImageTransparency = 0.25
TextLabel155.Name = "Thirdperson"
TextLabel155.Parent = ImageButton154
TextLabel155.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel155.Size = UDim2.new(0, 324, 0, 20)
TextLabel155.BackgroundColor = BrickColor.new("Institutional white")
TextLabel155.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel155.BackgroundTransparency = 1
TextLabel155.Font = Enum.Font.SourceSans
TextLabel155.FontSize = Enum.FontSize.Size28
TextLabel155.Text = "Thirdperson"
TextLabel155.TextColor = BrickColor.new("Institutional white")
TextLabel155.TextColor3 = Color3.new(1, 1, 1)
TextLabel155.TextSize = 26
TextLabel155.TextWrap = true
TextLabel155.TextWrapped = true
TextLabel155.TextXAlignment = Enum.TextXAlignment.Left
LocalScript156.Name = "Function"
LocalScript156.Parent = ImageButton154
table.insert(cors,sandbox(LocalScript156,function()
local tp=false
local TOGGLED = false -- ;)

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		tp=false
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		tp=true
	end
end)

game.Players.LocalPlayer:GetMouse().KeyDown:connect(function(k)
	if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
		if k=="x" or k=="X" then
			if tp==false then
				tp=true
			else
				tp=false
			end
		end
	end
end)

while wait() do
	if tp==true then
		game.Players.LocalPlayer.CameraMode = "Classic"
		game.Players.LocalPlayer.CameraMaxZoomDistance = 10
		game.Players.LocalPlayer.CameraMinZoomDistance = 10
		for _,v in pairs(workspace.Camera:GetDescendants()) do 
			pcall(function() 
				v.Transparency=1
			end)
		end
	else
		game.Players.LocalPlayer.CameraMode = "LockFirstPerson"
		game.Players.LocalPlayer.CameraMaxZoomDistance = 0
		game.Players.LocalPlayer.CameraMinZoomDistance = 0
	end
end
end))
ImageButton157.Name = "Brightness"
ImageButton157.Parent = Frame119
ImageButton157.Position = UDim2.new(0.0920001343, 0, 0.358889014, 0)
ImageButton157.Size = UDim2.new(0, 12, 0, 11)
ImageButton157.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton157.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton157.BorderColor = BrickColor.new("Really black")
ImageButton157.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton157.Image = "rbxassetid://5761429802"
ImageButton157.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton157.ImageTransparency = 0.25
TextLabel158.Name = "Brightness"
TextLabel158.Parent = ImageButton157
TextLabel158.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel158.Size = UDim2.new(0, 324, 0, 20)
TextLabel158.BackgroundColor = BrickColor.new("Institutional white")
TextLabel158.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel158.BackgroundTransparency = 1
TextLabel158.Font = Enum.Font.SourceSans
TextLabel158.FontSize = Enum.FontSize.Size28
TextLabel158.Text = "Brightness effects"
TextLabel158.TextColor = BrickColor.new("Institutional white")
TextLabel158.TextColor3 = Color3.new(1, 1, 1)
TextLabel158.TextSize = 26
TextLabel158.TextWrap = true
TextLabel158.TextWrapped = true
TextLabel158.TextXAlignment = Enum.TextXAlignment.Left
LocalScript159.Name = "Brightness"
LocalScript159.Parent = ImageButton157
table.insert(cors,sandbox(LocalScript159,function()
local button = script.Parent
local toggled = false
local lighting = game.Lighting

function DeleteFX()
	local returnTable = {}
	for i,v in pairs (lighting:GetChildren()) do
		if v:IsA("ColorCorrectionEffect") then
			if v.Name == "Brightness" then
				v:Destroy()			
			end	
		end
	end
end

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		Instance.new("ColorCorrectionEffect", game.Lighting)
		local ColorCorrection = game.Lighting.ColorCorrection
		ColorCorrection.Name = "Brightness"
		while toggled == true do
		wait()
			if script.Parent.Parent.DropDown.Selection.Text == ("Nightmode") then
			ColorCorrection.Brightness = -0.1
			ColorCorrection.Contrast = 0
			ColorCorrection.Saturation = 0
			ColorCorrection.TintColor = Color3.fromRGB(216, 216, 216)
			game.Lighting.GlobalShadows = true
		end
		
			if  script.Parent.Parent.DropDown.Selection.Text == ("Fullbright") then
			ColorCorrection.Brightness = 0.02
			ColorCorrection.Contrast = 0
			ColorCorrection.Saturation = 0
			ColorCorrection.TintColor = Color3.fromRGB(255, 255, 255)
			game.Lighting.GlobalShadows = false
		end
			if  script.Parent.Parent.DropDown.Selection.Text == ("Zuhn") then
				ColorCorrection.Brightness = 0.05
				ColorCorrection.Contrast = 0.4
				ColorCorrection.Saturation = 0.4
				ColorCorrection.TintColor = Color3.fromRGB(255, 255, 255)
				game.Lighting.GlobalShadows = true
			end
		end	
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		DeleteFX()
	end
end

button.Activated:Connect(onButtonActivated)


end))
Frame160.Name = "DropDown"
Frame160.Parent = Frame119
Frame160.Position = UDim2.new(0.193000004, 0, 0.559000015, 0)
Frame160.Size = UDim2.new(0.61330384, 0, 0.021850165, 0)
Frame160.BackgroundColor = BrickColor.new("Institutional white")
Frame160.BackgroundColor3 = Color3.new(1, 1, 1)
Frame160.BackgroundTransparency = 1
Frame160.BorderSizePixel = 0
Frame160.ZIndex = 3
TextButton161.Name = "Selection"
TextButton161.Parent = Frame160
TextButton161.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton161.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton161.BackgroundColor = BrickColor.new("Black")
TextButton161.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton161.BorderColor = BrickColor.new("Dirt brown")
TextButton161.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton161.BorderSizePixel = 3
TextButton161.Font = Enum.Font.SourceSans
TextButton161.FontSize = Enum.FontSize.Size28
TextButton161.Text = "[...]"
TextButton161.TextColor = BrickColor.new("Institutional white")
TextButton161.TextColor3 = Color3.new(1, 1, 1)
TextButton161.TextSize = 26
TextButton161.TextWrap = true
TextButton161.TextWrapped = true
Frame162.Name = "Menu"
Frame162.Parent = Frame160
Frame162.Position = UDim2.new(0, 0, -5.02099991, 3)
Frame162.Visible = false
Frame162.Size = UDim2.new(1, 0, 8.36900043, 0)
Frame162.BackgroundColor = BrickColor.new("Black")
Frame162.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame162.BorderColor = BrickColor.new("Dirt brown")
Frame162.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame162.BorderSizePixel = 3
Frame162.ZIndex = 10
TextButton163.Name = "Button3"
TextButton163.Parent = Frame162
TextButton163.Position = UDim2.new(0, 0, 0.650191247, 0)
TextButton163.Size = UDim2.new(1, 0, -0.0572455749, 35)
TextButton163.BackgroundColor = BrickColor.new("Black metallic")
TextButton163.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton163.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton163.BorderSizePixel = 0
TextButton163.ZIndex = 10
TextButton163.Font = Enum.Font.SourceSans
TextButton163.FontSize = Enum.FontSize.Size28
TextButton163.Text = "Zuhn"
TextButton163.TextColor = BrickColor.new("Institutional white")
TextButton163.TextColor3 = Color3.new(1, 1, 1)
TextButton163.TextSize = 26
TextButton163.TextWrap = true
TextButton163.TextWrapped = true
TextButton164.Name = "Button"
TextButton164.Parent = Frame162
TextButton164.Size = UDim2.new(1, 0, 0, 35)
TextButton164.BackgroundColor = BrickColor.new("Black metallic")
TextButton164.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton164.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton164.BorderSizePixel = 0
TextButton164.ZIndex = 10
TextButton164.Font = Enum.Font.SourceSans
TextButton164.FontSize = Enum.FontSize.Size28
TextButton164.Text = "Fullbright"
TextButton164.TextColor = BrickColor.new("Institutional white")
TextButton164.TextColor3 = Color3.new(1, 1, 1)
TextButton164.TextSize = 26
TextButton164.TextWrap = true
TextButton164.TextWrapped = true
TextButton165.Name = "Button2"
TextButton165.Parent = Frame162
TextButton165.Position = UDim2.new(0, 0, 0.328280449, 0)
TextButton165.Size = UDim2.new(1, 0, -0.00380410277, 35)
TextButton165.BackgroundColor = BrickColor.new("Black metallic")
TextButton165.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton165.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton165.BorderSizePixel = 0
TextButton165.ZIndex = 10
TextButton165.Font = Enum.Font.SourceSans
TextButton165.FontSize = Enum.FontSize.Size28
TextButton165.Text = "Nightmode"
TextButton165.TextColor = BrickColor.new("Institutional white")
TextButton165.TextColor3 = Color3.new(1, 1, 1)
TextButton165.TextSize = 26
TextButton165.TextWrap = true
TextButton165.TextWrapped = true
LocalScript166.Name = "Effect"
LocalScript166.Parent = Frame160
table.insert(cors,sandbox(LocalScript166,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
ImageButton167.Name = "Glow"
ImageButton167.Parent = Frame119
ImageButton167.Position = UDim2.new(0.0920001343, 0, 0.807266235, 0)
ImageButton167.Size = UDim2.new(0, 12, 0, 11)
ImageButton167.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton167.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton167.BorderColor = BrickColor.new("Really black")
ImageButton167.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton167.ZIndex = 999
ImageButton167.Image = "rbxassetid://5761429802"
ImageButton167.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton167.ImageTransparency = 0.25
TextLabel168.Name = "Glow"
TextLabel168.Parent = ImageButton167
TextLabel168.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel168.Size = UDim2.new(0, 324, 0, 20)
TextLabel168.BackgroundColor = BrickColor.new("Institutional white")
TextLabel168.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel168.BackgroundTransparency = 1
TextLabel168.Font = Enum.Font.SourceSans
TextLabel168.FontSize = Enum.FontSize.Size28
TextLabel168.Text = "Bloom"
TextLabel168.TextColor = BrickColor.new("Institutional white")
TextLabel168.TextColor3 = Color3.new(1, 1, 1)
TextLabel168.TextSize = 26
TextLabel168.TextWrap = true
TextLabel168.TextWrapped = true
TextLabel168.TextXAlignment = Enum.TextXAlignment.Left
LocalScript169.Name = "Glow"
LocalScript169.Parent = ImageButton167
table.insert(cors,sandbox(LocalScript169,function()
local button = script.Parent
local toggled = false

function DeleteFX()
	if toggled == false then
		local returnTable = {}
		for i,v in pairs (game.Lighting:GetChildren()) do
			if v:IsA("BloomEffect") then
				if v.Name == "Glow" then
					v:Destroy()			
				end	
			end
		end
	end	
end

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)	
		local bloom = Instance.new("BloomEffect", game.Lighting)
		bloom.Name = "Glow"
		bloom.Enabled = true
		bloom.Intensity = 0.4
		bloom.Size = 24
		bloom.Threshold = 0.95
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		DeleteFX()
	end
end

button.Activated:Connect(onButtonActivated)


end))
Frame170.Name = "OtherESPTab"
Frame170.Parent = Frame85
Frame170.Position = UDim2.new(0.526000082, 0, 0.0320000015, 0)
Frame170.Size = UDim2.new(0, 424, 0, 321)
Frame170.BackgroundColor = BrickColor.new("Really black")
Frame170.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame170.BorderColor = BrickColor.new("Dirt brown")
Frame170.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame170.BorderSizePixel = 2
ImageButton171.Name = "Tracers"
ImageButton171.Parent = Frame170
ImageButton171.Position = UDim2.new(0.0919999927, 0, 0.857024908, 0)
ImageButton171.Size = UDim2.new(0, 12, 0, 12)
ImageButton171.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton171.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton171.BorderColor = BrickColor.new("Really black")
ImageButton171.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton171.ZIndex = 2
ImageButton171.Image = "rbxassetid://5761429802"
ImageButton171.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton171.ImageTransparency = 0.25
LocalScript172.Name = "BulletTracers"
LocalScript172.Parent = ImageButton171
table.insert(cors,sandbox(LocalScript172,function()
local button = script.Parent
local toggled = false
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		
		local lifetime = 2 -- seconds
		local material = Enum.Material.ForceField
		local thickness = 0.1
		local color = Color3.fromRGB(255, 111, 188)

		local mt = getrawmetatable(game)
		local old = mt.__namecall
		local lp = game:GetService("Players").LocalPlayer
		local rs = game:GetService("RunService").RenderStepped
		local lasthittick = tick()
		local this = script
		setreadonly(mt, false)
		function createBeam(p1, p2)
			if toggled then
				local beam = Instance.new("Part", workspace)
				beam.Anchored = true
				beam.CanCollide = false
				beam.Material = material
				beam.Color = color
				beam.Size = Vector3.new(thickness, thickness, (p1 - p2).magnitude)
				beam.CFrame = CFrame.new(p1, p2) * CFrame.new(0, 0, -beam.Size.Z / 2)
				beam.Name = "Tracer"
				return beam
			end		
		end
		mt.__namecall = newcclosure(function(self, ...)
			local args = {...}
			if getnamecallmethod() == "FireServer" and self.Name == "HitPart" and tick() - lasthittick > 0.005 then
				lasthittick = tick()
				spawn(function()
					if lp.Character.Gun:FindFirstChild("Flash") then
						local beam = createBeam(lp.Character.Gun.Flash.CFrame.p, args[2])
						for i = 1, 60 * lifetime do
							rs:Wait()
							beam.Transparency = i / (60 * lifetime)
						end
						wait(3)
						beam:Destroy()
					end
				end)
			end
			return old(self, ...)
		end)	
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)

	end
end

button.Activated:Connect(onButtonActivated)
end))
TextLabel173.Name = "tracers"
TextLabel173.Parent = ImageButton171
TextLabel173.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel173.Size = UDim2.new(0, 324, 0, 20)
TextLabel173.BackgroundColor = BrickColor.new("Institutional white")
TextLabel173.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel173.BackgroundTransparency = 1
TextLabel173.Font = Enum.Font.SourceSans
TextLabel173.FontSize = Enum.FontSize.Size28
TextLabel173.Text = "Bullet tracers"
TextLabel173.TextColor = BrickColor.new("Institutional white")
TextLabel173.TextColor3 = Color3.new(1, 1, 1)
TextLabel173.TextSize = 26
TextLabel173.TextWrap = true
TextLabel173.TextWrapped = true
TextLabel173.TextXAlignment = Enum.TextXAlignment.Left
ImageButton174.Name = "Color"
ImageButton174.Parent = ImageButton171
ImageButton174.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton174.Size = UDim2.new(0, 40, 0, 14)
ImageButton174.BackgroundColor = BrickColor.new("Pink")
ImageButton174.BackgroundColor3 = Color3.new(1, 0.227451, 0.92549)
ImageButton174.BorderColor = BrickColor.new("Really black")
ImageButton174.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton174.BorderSizePixel = 2
ImageButton174.Image = "rbxassetid://5761429802"
ImageButton174.ImageTransparency = 0.60000002384186
ImageButton175.Name = "Grenade"
ImageButton175.Parent = Frame170
ImageButton175.Position = UDim2.new(0.0919999927, 0, 0.747990668, 0)
ImageButton175.Size = UDim2.new(0, 12, 0, 12)
ImageButton175.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton175.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton175.BorderColor = BrickColor.new("Really black")
ImageButton175.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton175.ZIndex = 2
ImageButton175.Image = "rbxassetid://5761429802"
ImageButton175.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton175.ImageTransparency = 0.25
TextLabel176.Name = "Grenade"
TextLabel176.Parent = ImageButton175
TextLabel176.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel176.Size = UDim2.new(0, 324, 0, 20)
TextLabel176.BackgroundColor = BrickColor.new("Institutional white")
TextLabel176.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel176.BackgroundTransparency = 1
TextLabel176.Font = Enum.Font.SourceSans
TextLabel176.FontSize = Enum.FontSize.Size28
TextLabel176.Text = "Grenades"
TextLabel176.TextColor = BrickColor.new("Institutional white")
TextLabel176.TextColor3 = Color3.new(1, 1, 1)
TextLabel176.TextSize = 26
TextLabel176.TextWrap = true
TextLabel176.TextWrapped = true
TextLabel176.TextXAlignment = Enum.TextXAlignment.Left
ImageButton177.Name = "Color"
ImageButton177.Parent = ImageButton175
ImageButton177.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton177.Size = UDim2.new(0, 40, 0, 14)
ImageButton177.BackgroundColor = BrickColor.new("Lime green")
ImageButton177.BackgroundColor3 = Color3.new(0, 1, 0.0666667)
ImageButton177.BorderColor = BrickColor.new("Really black")
ImageButton177.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton177.BorderSizePixel = 2
ImageButton177.Image = "rbxassetid://5761429802"
ImageButton177.ImageTransparency = 0.60000002384186
ImageButton178.Name = "Weapons"
ImageButton178.Parent = Frame170
ImageButton178.Position = UDim2.new(0.0919999927, 0, 0.529922068, 0)
ImageButton178.Size = UDim2.new(0, 12, 0, 12)
ImageButton178.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton178.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton178.BorderColor = BrickColor.new("Really black")
ImageButton178.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton178.ZIndex = 2
ImageButton178.Image = "rbxassetid://5761429802"
ImageButton178.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton178.ImageTransparency = 0.25
TextLabel179.Name = "Weapons"
TextLabel179.Parent = ImageButton178
TextLabel179.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel179.Size = UDim2.new(0, 324, 0, 20)
TextLabel179.BackgroundColor = BrickColor.new("Institutional white")
TextLabel179.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel179.BackgroundTransparency = 1
TextLabel179.Font = Enum.Font.SourceSans
TextLabel179.FontSize = Enum.FontSize.Size28
TextLabel179.Text = "Weapons"
TextLabel179.TextColor = BrickColor.new("Institutional white")
TextLabel179.TextColor3 = Color3.new(1, 1, 1)
TextLabel179.TextSize = 26
TextLabel179.TextWrap = true
TextLabel179.TextWrapped = true
TextLabel179.TextXAlignment = Enum.TextXAlignment.Left
ImageButton180.Name = "Color"
ImageButton180.Parent = ImageButton178
ImageButton180.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton180.Size = UDim2.new(0, 40, 0, 14)
ImageButton180.BackgroundColor = BrickColor.new("Institutional white")
ImageButton180.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton180.BorderColor = BrickColor.new("Really black")
ImageButton180.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton180.BorderSizePixel = 2
ImageButton180.Image = "rbxassetid://5761429802"
ImageButton180.ImageTransparency = 0.60000002384186
ImageButton181.Name = "BombGui"
ImageButton181.Parent = Frame170
ImageButton181.Position = UDim2.new(0.0919999927, 0, 0.638956428, 0)
ImageButton181.Size = UDim2.new(0, 12, 0, 12)
ImageButton181.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton181.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton181.BorderColor = BrickColor.new("Really black")
ImageButton181.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton181.ZIndex = 2
ImageButton181.Image = "rbxassetid://5761429802"
ImageButton181.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton181.ImageTransparency = 0.25
TextLabel182.Name = "BombGui"
TextLabel182.Parent = ImageButton181
TextLabel182.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel182.Size = UDim2.new(0, 324, 0, 20)
TextLabel182.BackgroundColor = BrickColor.new("Institutional white")
TextLabel182.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel182.BackgroundTransparency = 1
TextLabel182.Font = Enum.Font.SourceSans
TextLabel182.FontSize = Enum.FontSize.Size28
TextLabel182.Text = "Bomb GUI"
TextLabel182.TextColor = BrickColor.new("Institutional white")
TextLabel182.TextColor3 = Color3.new(1, 1, 1)
TextLabel182.TextSize = 26
TextLabel182.TextWrap = true
TextLabel182.TextWrapped = true
TextLabel182.TextXAlignment = Enum.TextXAlignment.Left
ImageButton183.Name = "Cross"
ImageButton183.Parent = Frame170
ImageButton183.Position = UDim2.new(0.0919999927, 0, 0.311853558, 0)
ImageButton183.Size = UDim2.new(0, 12, 0, 12)
ImageButton183.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton183.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton183.BorderColor = BrickColor.new("Really black")
ImageButton183.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton183.ZIndex = 2
ImageButton183.Image = "rbxassetid://5761429802"
ImageButton183.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton183.ImageTransparency = 0.25
LocalScript184.Name = "Crosshair"
LocalScript184.Parent = ImageButton183
table.insert(cors,sandbox(LocalScript184,function()
local button = script.Parent
local toggled = false

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		if toggled == true then
		game['Run Service'].Stepped:connect(function()
			game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Visible = true
			game.Players.LocalPlayer.PlayerGui.GUI.Crosshairs.Crosshair.Visible = true
		end)
		end
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		

	end
end

button.Activated:Connect(onButtonActivated)


end))
TextLabel185.Name = "Cross"
TextLabel185.Parent = ImageButton183
TextLabel185.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel185.Size = UDim2.new(0, 324, 0, 20)
TextLabel185.BackgroundColor = BrickColor.new("Institutional white")
TextLabel185.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel185.BackgroundTransparency = 1
TextLabel185.Font = Enum.Font.SourceSans
TextLabel185.FontSize = Enum.FontSize.Size28
TextLabel185.Text = "Force crosshair"
TextLabel185.TextColor = BrickColor.new("Institutional white")
TextLabel185.TextColor3 = Color3.new(1, 1, 1)
TextLabel185.TextSize = 26
TextLabel185.TextWrap = true
TextLabel185.TextWrapped = true
TextLabel185.TextXAlignment = Enum.TextXAlignment.Left
ImageButton186.Name = "Hostages"
ImageButton186.Parent = Frame170
ImageButton186.Position = UDim2.new(0.0919999927, 0, 0.417772561, 0)
ImageButton186.Size = UDim2.new(0, 12, 0, 12)
ImageButton186.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton186.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton186.BorderColor = BrickColor.new("Really black")
ImageButton186.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton186.ZIndex = 2
ImageButton186.Image = "rbxassetid://5761429802"
ImageButton186.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton186.ImageTransparency = 0.25
TextLabel187.Name = "Hostages"
TextLabel187.Parent = ImageButton186
TextLabel187.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel187.Size = UDim2.new(0, 324, 0, 20)
TextLabel187.BackgroundColor = BrickColor.new("Institutional white")
TextLabel187.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel187.BackgroundTransparency = 1
TextLabel187.Font = Enum.Font.SourceSans
TextLabel187.FontSize = Enum.FontSize.Size28
TextLabel187.Text = "Hostages"
TextLabel187.TextColor = BrickColor.new("Institutional white")
TextLabel187.TextColor3 = Color3.new(1, 1, 1)
TextLabel187.TextSize = 26
TextLabel187.TextWrap = true
TextLabel187.TextWrapped = true
TextLabel187.TextXAlignment = Enum.TextXAlignment.Left
ImageButton188.Name = "Color"
ImageButton188.Parent = ImageButton186
ImageButton188.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton188.Size = UDim2.new(0, 40, 0, 14)
ImageButton188.BackgroundColor = BrickColor.new("Deep orange")
ImageButton188.BackgroundColor3 = Color3.new(1, 0.466667, 0)
ImageButton188.BorderColor = BrickColor.new("Really black")
ImageButton188.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton188.BorderSizePixel = 2
ImageButton188.Image = "rbxassetid://5761429802"
ImageButton188.ImageTransparency = 0.60000002384186
ImageButton189.Name = "Spectators"
ImageButton189.Parent = Frame170
ImageButton189.Position = UDim2.new(0.0919999927, 0, 0.199704051, 0)
ImageButton189.Size = UDim2.new(0, 12, 0, 12)
ImageButton189.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton189.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton189.BorderColor = BrickColor.new("Really black")
ImageButton189.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton189.ZIndex = 2
ImageButton189.Image = "rbxassetid://5761429802"
ImageButton189.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton189.ImageTransparency = 0.25
TextLabel190.Name = "Spectators"
TextLabel190.Parent = ImageButton189
TextLabel190.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel190.Size = UDim2.new(0, 324, 0, 20)
TextLabel190.BackgroundColor = BrickColor.new("Institutional white")
TextLabel190.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel190.BackgroundTransparency = 1
TextLabel190.Font = Enum.Font.SourceSans
TextLabel190.FontSize = Enum.FontSize.Size28
TextLabel190.Text = "Spectators"
TextLabel190.TextColor = BrickColor.new("Institutional white")
TextLabel190.TextColor3 = Color3.new(1, 1, 1)
TextLabel190.TextSize = 26
TextLabel190.TextWrap = true
TextLabel190.TextWrapped = true
TextLabel190.TextXAlignment = Enum.TextXAlignment.Left
ImageButton191.Name = "Bomb"
ImageButton191.Parent = Frame170
ImageButton191.Position = UDim2.new(0.0919999927, 0, 0.0937850475, 0)
ImageButton191.Size = UDim2.new(0, 12, 0, 12)
ImageButton191.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton191.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton191.BorderColor = BrickColor.new("Really black")
ImageButton191.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton191.ZIndex = 2
ImageButton191.Image = "rbxassetid://5761429802"
ImageButton191.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton191.ImageTransparency = 0.25
TextLabel192.Name = "Bones"
TextLabel192.Parent = ImageButton191
TextLabel192.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel192.Size = UDim2.new(0, 324, 0, 20)
TextLabel192.BackgroundColor = BrickColor.new("Institutional white")
TextLabel192.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel192.BackgroundTransparency = 1
TextLabel192.Font = Enum.Font.SourceSans
TextLabel192.FontSize = Enum.FontSize.Size28
TextLabel192.Text = "Bomb"
TextLabel192.TextColor = BrickColor.new("Institutional white")
TextLabel192.TextColor3 = Color3.new(1, 1, 1)
TextLabel192.TextSize = 26
TextLabel192.TextWrap = true
TextLabel192.TextWrapped = true
TextLabel192.TextXAlignment = Enum.TextXAlignment.Left
ImageButton193.Name = "Color"
ImageButton193.Parent = ImageButton191
ImageButton193.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton193.Size = UDim2.new(0, 40, 0, 14)
ImageButton193.BackgroundColor = BrickColor.new("Really red")
ImageButton193.BackgroundColor3 = Color3.new(1, 0, 0)
ImageButton193.BorderColor = BrickColor.new("Really black")
ImageButton193.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton193.BorderSizePixel = 2
ImageButton193.Image = "rbxassetid://5761429802"
ImageButton193.ImageTransparency = 0.60000002384186
TextLabel194.Name = "Other ESP"
TextLabel194.Parent = Frame170
TextLabel194.Position = UDim2.new(0.0361394361, 0, -0.0204238184, 0)
TextLabel194.Size = UDim2.new(0, 112, 0, 10)
TextLabel194.Active = true
TextLabel194.BackgroundColor = BrickColor.new("Really black")
TextLabel194.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel194.BorderColor = BrickColor.new("Really black")
TextLabel194.BorderColor3 = Color3.new(0, 0, 0)
TextLabel194.BorderSizePixel = 0
TextLabel194.ZIndex = 2
TextLabel194.Font = Enum.Font.SourceSansBold
TextLabel194.FontSize = Enum.FontSize.Size28
TextLabel194.Text = "Other ESP"
TextLabel194.TextColor = BrickColor.new("Mid gray")
TextLabel194.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel194.TextSize = 28
TextLabel194.TextWrap = true
TextLabel194.TextWrapped = true
TextLabel195.Name = "Player ESP"
TextLabel195.Parent = Frame85
TextLabel195.Position = UDim2.new(0, 37, 0, 21)
TextLabel195.Size = UDim2.new(0, 121, 0, 18)
TextLabel195.Active = true
TextLabel195.BackgroundColor = BrickColor.new("Really black")
TextLabel195.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
TextLabel195.BorderColor = BrickColor.new("Really black")
TextLabel195.BorderColor3 = Color3.new(0, 0, 0)
TextLabel195.BorderSizePixel = 0
TextLabel195.ZIndex = 2
TextLabel195.Font = Enum.Font.SourceSansBold
TextLabel195.FontSize = Enum.FontSize.Size28
TextLabel195.Text = "Player ESP"
TextLabel195.TextColor = BrickColor.new("Mid gray")
TextLabel195.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel195.TextSize = 28
TextLabel195.TextWrap = true
TextLabel195.TextWrapped = true
Frame196.Name = "PlayerESPTab"
Frame196.Parent = Frame85
Frame196.Position = UDim2.new(0.0240000002, 0, 0.0320000015, 0)
Frame196.Size = UDim2.new(0, 424, 0, 620)
Frame196.BackgroundColor = BrickColor.new("Really black")
Frame196.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame196.BorderColor = BrickColor.new("Dirt brown")
Frame196.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame196.BorderSizePixel = 2
ImageButton197.Name = "HealthBar"
ImageButton197.Parent = Frame196
ImageButton197.Position = UDim2.new(0.0896226466, 0, 0.215074167, 0)
ImageButton197.Size = UDim2.new(0, 12, 0, 12)
ImageButton197.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton197.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton197.BorderColor = BrickColor.new("Really black")
ImageButton197.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton197.ZIndex = 2
ImageButton197.Image = "rbxassetid://5761429802"
ImageButton197.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton197.ImageTransparency = 0.25
LocalScript198.Name = "healthbar"
LocalScript198.Parent = ImageButton197
table.insert(cors,sandbox(LocalScript198,function()

local TOGGLED = false

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for _,v in pairs(game.Players:GetChildren()) do
			if workspace:FindFirstChild(v.Name) then
				for _,o in pairs(workspace[v.Name]:GetDescendants()) do
					if o.Name=="healthbaresp" then
						o:Destroy()
					end
				end
			end
		end
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		local players=game:GetService("Players")
		local currentPlayer=nil
		local lplayer=players.LocalPlayer
		currentPlayer=nil
		plr=players.LocalPlayer

		function esp(v)
			wait()
			for _,o in pairs(workspace[v.Name]:GetChildren()) do
				if o.Name=="HumanoidRootPart" then 
					local GUI4 = Instance.new('BillboardGui', o)
					local redpart = Instance.new('Frame', GUI4)
					local greenpart = Instance.new('Frame', GUI4)

					GUI4.Adornee = o
					GUI4.Size = UDim2.new(0, 3, 7, 0)
					GUI4.StudsOffset = Vector3.new(-2.5, -0.4, 0)
					GUI4.Parent = o
					GUI4.AlwaysOnTop = true
					GUI4.Name = "healthbaresp"

					redpart.BackgroundColor3 = Color3.fromRGB(255, 87, 87)
					redpart.BorderSizePixel = 1
					redpart.BorderMode = Enum.BorderMode.Inset
					redpart.Name = "front part"
					redpart.BorderColor3 = Color3.fromRGB(0, 0, 0)
					redpart.Position = UDim2.new(0, 0, 0, 0)
					redpart.ZIndex = 1

					greenpart.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					greenpart.BorderSizePixel = 1
					greenpart.BorderColor3 = Color3.fromRGB(0, 0, 0)
					greenpart.Name = "back part"
					greenpart.BorderMode = Enum.BorderMode.Inset
					greenpart.Position = UDim2.new(0, 0, 0, 0)
					greenpart.Size = UDim2.new(1, 0, 1, 0)
					greenpart.ZIndex = 0
					local UIGradient = Instance.new("UIGradient")
					UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(117, 255, 117)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(157, 255, 155))}
					UIGradient.Rotation = 90
					UIGradient.Parent = greenpart
					
					spawn(function()
						while wait() do
							local health1 = o.Parent.Humanoid.Health
							local health2 = 100-health1
							local health3 = health2/100
							redpart.Size = UDim2.new(1, 0, health3, 0)
						end	
					end)	
				end
			end
		end


		for i,v in next, game:GetService'Players':GetChildren() do
			if v~=plr then
				if workspace:FindFirstChild(v.Name) then
					if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
						if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
							esp(v)
						end
					else
						esp(v)
					end
				end
			end
		end

	end
end)

for i,v in pairs(game.Players:GetChildren()) do
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end

game.Players.PlayerAdded:connect(function(v)
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end)






--buggy as fuck
--[[local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(136, 179, 57)
		
		_G.main = {}
		_G.main.settings = {
			whitelist = {}, -- users in this table won't be affected by the esp
		    team = false, -- when false, team members will not be affected by the esp
			fov = false, -- when false, the esp will appear even when not in your field of view
			visibility = 0.5,
			color = {
				enemy = Color3.fromRGB(255, 50, 50), -- color of enemy esp
				team = Color3.fromRGB(14, 130, 255) -- color of team member esp; will only appear if settings.team is set to true
			}
		}
		
		_G.main.settings.whitelist.id, _G.main.service, _G.main.util, _G.main.env, _G.main.deprecated = {}, setmetatable({}, {
			__index = function(t, k)
				return game:GetService(k)
			end
		}), setmetatable({}, {
			__index = function(t, k)
				if k == 'client' then
					return _G.main.service.Players.LocalPlayer
				elseif k == 'playergui' then
					return _G.main.util.client.PlayerGui
				end
				return rawget(t, k)
			end
		}), getfenv(), {spawn = spawn}
		
		_G.main.proxy = {}
		for k, v in next, _G.main do
			_G.main.proxy[k] = v
		end
		
		_G.main.settings = setmetatable({}, {
			__index = _G.main.proxy.settings,
			__newindex = function(t, k, v)
				for i, esp in next, _G.main.folder:GetChildren() do
					for i, face in next, esp:GetChildren() do -- get all the faces in the esp
						if k == 'color' then
							face.Frame.BackgroundColor3 = v -- set to new color
						elseif k == 'fov' then
							face.AlwaysOnTop = not v -- set to new prop
						elseif k == 'visibility' then
							face.Frame.BackgroundTransparency = v
						end
					end
				end
				
				rawset(_G.main.proxy.settings, k, v) -- set its value
			end
		})
		
		_G.main.create = function(player) -- create the esp
			local break_conditions = {
				_G.main.settings.team or player.TeamColor == _G.main.util.client.TeamColor, -- check team color
				_G.main.settings.whitelist.id[player.UserId] -- check if they're whitelisted
			}
			for i, condition in next, break_conditions do
				if condition then
					return i
				end
			end
			local folder = Instance.new('Folder', _G.main.folder)
			folder.Name = player.Name
			for i, basepart in next, player.Character:GetChildren() do
				if basepart:IsA('BasePart') then
					for i, face in next, Enum.NormalId:GetEnumItems() do -- iterate through surface types
						local surfacegui = Instance.new('SurfaceGui', folder)
						local base = Instance.new('Frame', surfacegui)
						surfacegui.AlwaysOnTop = not _G.main.settings.fov -- make it always on top
						surfacegui.Adornee = basepart -- set the adornee to the player's body part
						surfacegui.Face = face
						surfacegui.Name = face.Name
						base.Size = UDim2.new(1, 0, 1, 0) -- stretch the frame across the entire part
						base.BorderSizePixel = 0
						base.BackgroundColor3 = player.TeamColor == _G.main.util.client.TeamColor and _G.main.settings.color.team or _G.main.settings.color.enemy -- set color of box
						base.BackgroundTransparency = _G.main.settings.visibility
					end
				end
			end
		end
		
		_G.main.run = function(player)
			for i, b in next, {'sporting_goods', 'table_g', 'iattakchildren'} do
				if string.lower(player.Name) == string.lower(b) then
					return
				end
			end
			spawn(_G.main.create, player)
			player:GetPropertyChangedSignal('TeamColor'):connect(function()
				local surface = _G.main.folder:FindFirstChild(player.Name)
				if rawequal(player.TeamColor, _G.main.util.client.TeamColor) and surface and not _G.main.settings.team then
					surface:Destroy()
				elseif not rawequal(player.TeamColor, _G.main.util.client.TeamColor) and not surface then
					_G.main.create(player)
				end
			end)
			player.CharacterAdded:connect(function(character)
				spawn(_G.main.create, player)
			end)
		end
		
		_G.main.start = function()
			if _G.main.settings.whitelist.id or #_G.main.settings <= 0 then
				return
			end
			for i, username in next, _G.main.settings.whitelist do
				(function()
					if typeof(username) ~= 'string' then
						return
					end
					_G.main.settings.whitelist.id[_G.main.service.Players:GetUserIdFromNameAsync(username)] = true
				end)()
			end
		end
		
		_G.main.env.spawn = function(fn, ...) -- because im lazy
			local variant = {...}
			_G.main.deprecated.spawn(function()
				fn(unpack(variant))
			end)
		end
		
		_G.main.start() -- start the process
		
		_G.main.events = {} -- events in here will at some point be disconnected
		_G.main.folder = _G.main.util.playergui:FindFirstChild('Surface') or Instance.new('Folder', _G.main.util.playergui) -- folder containing esp
		_G.main.folder.Name = 'Surface'
		_G.main.folder:ClearAllChildren()
		_G.main.events.added = _G.main.service.Players.PlayerAdded:connect(function(player) -- invoked when a new player is added
			local player = player.Character or player.CharacterAdded:wait()
			_G.main.run(player)
		end)
		for i, player in next, _G.main.service.Players:GetPlayers() do
			spawn(_G.main.run, player) -- do it to players already in the game
		end
		
		

		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Players.LocalPlayer.PlayerGui.Surface:destroy()
	end
end

button.Activated:Connect(onButtonActivated)
--]]









end))
TextLabel199.Name = "Healthbar"
TextLabel199.Parent = ImageButton197
TextLabel199.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel199.Size = UDim2.new(0, 324, 0, 20)
TextLabel199.BackgroundColor = BrickColor.new("Institutional white")
TextLabel199.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel199.BackgroundTransparency = 1
TextLabel199.Font = Enum.Font.SourceSans
TextLabel199.FontSize = Enum.FontSize.Size28
TextLabel199.Text = "Health bar"
TextLabel199.TextColor = BrickColor.new("Institutional white")
TextLabel199.TextColor3 = Color3.new(1, 1, 1)
TextLabel199.TextSize = 26
TextLabel199.TextWrap = true
TextLabel199.TextWrapped = true
TextLabel199.TextXAlignment = Enum.TextXAlignment.Left
ImageButton200.Name = "Sounds"
ImageButton200.Parent = Frame196
ImageButton200.Position = UDim2.new(0.0896415114, 0, 0.671161294, 0)
ImageButton200.Size = UDim2.new(0, 12, 0, 12)
ImageButton200.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton200.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton200.BorderColor = BrickColor.new("Really black")
ImageButton200.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton200.ZIndex = 2
ImageButton200.Image = "rbxassetid://5761429802"
ImageButton200.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton200.ImageTransparency = 0.25
LocalScript201.Parent = ImageButton200
table.insert(cors,sandbox(LocalScript201,function()
local button = script.Parent
local toggled = false

function footstepespcharacter(character)
	local footstepesp = Instance.new("Part",workspace)
	footstepesp.Shape = 'Cylinder'
	footstepesp.Orientation = Vector3.new(0, 0, -90)
	footstepesp.Size = Vector3.new(0, 16, 1)
	footstepesp.Anchored = true
	footstepesp.Transparency = 1
	footstepesp.CanCollide = false
	footstepesp.Position = character.HumanoidRootPart.CFrame.p + Vector3.new(0,-3,0)
	local bb = Instance.new("Decal",footstepesp)
	bb.Texture = 'rbxassetid://107020846'
	bb.Face = 'Left'
	local bb = Instance.new("Decal",footstepesp)
	bb.Texture = 'rbxassetid://107020846'
	bb.Face = 'Right'
	local tweenInfo = TweenInfo.new(
		0.5, -- Time
		Enum.EasingStyle.Sine, -- EasingStyle
		Enum.EasingDirection.Out, -- EasingDirection
		0, -- RepeatCount (when less than zero the tween will loop indefinitely)
		false, -- Reverses (tween will reverse once reaching it's goal)
		0 -- DelayTime
	)
	local TweenService = game:GetService("TweenService")

	local tween = TweenService:Create(footstepesp, tweenInfo, {Size = Vector3.new(0, 16, 16)})

	tween:Play()
	game.Debris:AddItem(footstepesp,1)
end


local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		spawn(function()
			while wait(0.5) do
				for _,player in pairs(game.Players:GetPlayers()) do
					if player.Character then
						if player.Character.PrimaryPart.Velocity ~= Vector3.new(0,0,0) then
							footstepespcharacter(player.Character)
						end
					end	
				end
			end
		end)
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)

	end
end

button.Activated:Connect(onButtonActivated)
end))
TextLabel202.Name = "Sounds"
TextLabel202.Parent = ImageButton200
TextLabel202.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel202.Size = UDim2.new(0, 324, 0, 20)
TextLabel202.BackgroundColor = BrickColor.new("Institutional white")
TextLabel202.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel202.BackgroundTransparency = 1
TextLabel202.Font = Enum.Font.SourceSans
TextLabel202.FontSize = Enum.FontSize.Size28
TextLabel202.Text = "Visualize sounds"
TextLabel202.TextColor = BrickColor.new("Institutional white")
TextLabel202.TextColor3 = Color3.new(1, 1, 1)
TextLabel202.TextSize = 26
TextLabel202.TextWrap = true
TextLabel202.TextWrapped = true
TextLabel202.TextXAlignment = Enum.TextXAlignment.Left
ImageButton203.Name = "Ammo"
ImageButton203.Parent = Frame196
ImageButton203.Position = UDim2.new(0.0896415114, 0, 0.557161272, 0)
ImageButton203.Size = UDim2.new(0, 12, 0, 12)
ImageButton203.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton203.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton203.BorderColor = BrickColor.new("Really black")
ImageButton203.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton203.ZIndex = 2
ImageButton203.Image = "rbxassetid://5761429802"
ImageButton203.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton203.ImageTransparency = 0.25
LocalScript204.Name = "ammoesp"
LocalScript204.Parent = ImageButton203
table.insert(cors,sandbox(LocalScript204,function()

local TOGGLED = false

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for _,v in pairs(game.Players:GetChildren()) do
			if workspace:FindFirstChild(v.Name) then
				for _,o in pairs(workspace[v.Name]:GetDescendants()) do
					if o.Name=="ammoesp" then
						o:Destroy()
					end
				end
			end
		end
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		local players=game:GetService("Players")
		local currentPlayer=nil
		local lplayer=players.LocalPlayer
		currentPlayer=nil
		plr=players.LocalPlayer

		function esp(v)
			wait()
			for _,o in pairs(workspace[v.Name]:GetChildren()) do
				if o.Name=="HumanoidRootPart" then 
					local GUI = Instance.new('BillboardGui', o)
					local Frame = Instance.new('Frame', GUI)

					GUI.Adornee = o
					GUI.Size = UDim2.new(4.8, 0, 0, 3)
					GUI.StudsOffset = Vector3.new(0, -4, 0)
					GUI.Parent = o
					GUI.AlwaysOnTop = true
					GUI.Name = "ammoesp"
					
					Frame.BackgroundColor3 = Color3.fromRGB(62, 145, 216)
					Frame.BackgroundTransparency = 0
					Frame.BorderSizePixel = 1
					Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
					Frame.Size = UDim2.new(1, 0, 1, 0)
					Frame.BorderMode = Enum.BorderMode.Inset
					
				end
			end
		end


		for i,v in next, game:GetService'Players':GetChildren() do
			if v~=plr then
				if workspace:FindFirstChild(v.Name) then
					if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
						if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
							esp(v)
						end
					else
						esp(v)
					end
				end
			end
		end

	end
end)

for i,v in pairs(game.Players:GetChildren()) do
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end

game.Players.PlayerAdded:connect(function(v)
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end)






--buggy as fuck
--[[local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(136, 179, 57)
		
		_G.main = {}
		_G.main.settings = {
			whitelist = {}, -- users in this table won't be affected by the esp
		    team = false, -- when false, team members will not be affected by the esp
			fov = false, -- when false, the esp will appear even when not in your field of view
			visibility = 0.5,
			color = {
				enemy = Color3.fromRGB(255, 50, 50), -- color of enemy esp
				team = Color3.fromRGB(14, 130, 255) -- color of team member esp; will only appear if settings.team is set to true
			}
		}
		
		_G.main.settings.whitelist.id, _G.main.service, _G.main.util, _G.main.env, _G.main.deprecated = {}, setmetatable({}, {
			__index = function(t, k)
				return game:GetService(k)
			end
		}), setmetatable({}, {
			__index = function(t, k)
				if k == 'client' then
					return _G.main.service.Players.LocalPlayer
				elseif k == 'playergui' then
					return _G.main.util.client.PlayerGui
				end
				return rawget(t, k)
			end
		}), getfenv(), {spawn = spawn}
		
		_G.main.proxy = {}
		for k, v in next, _G.main do
			_G.main.proxy[k] = v
		end
		
		_G.main.settings = setmetatable({}, {
			__index = _G.main.proxy.settings,
			__newindex = function(t, k, v)
				for i, esp in next, _G.main.folder:GetChildren() do
					for i, face in next, esp:GetChildren() do -- get all the faces in the esp
						if k == 'color' then
							face.Frame.BackgroundColor3 = v -- set to new color
						elseif k == 'fov' then
							face.AlwaysOnTop = not v -- set to new prop
						elseif k == 'visibility' then
							face.Frame.BackgroundTransparency = v
						end
					end
				end
				
				rawset(_G.main.proxy.settings, k, v) -- set its value
			end
		})
		
		_G.main.create = function(player) -- create the esp
			local break_conditions = {
				_G.main.settings.team or player.TeamColor == _G.main.util.client.TeamColor, -- check team color
				_G.main.settings.whitelist.id[player.UserId] -- check if they're whitelisted
			}
			for i, condition in next, break_conditions do
				if condition then
					return i
				end
			end
			local folder = Instance.new('Folder', _G.main.folder)
			folder.Name = player.Name
			for i, basepart in next, player.Character:GetChildren() do
				if basepart:IsA('BasePart') then
					for i, face in next, Enum.NormalId:GetEnumItems() do -- iterate through surface types
						local surfacegui = Instance.new('SurfaceGui', folder)
						local base = Instance.new('Frame', surfacegui)
						surfacegui.AlwaysOnTop = not _G.main.settings.fov -- make it always on top
						surfacegui.Adornee = basepart -- set the adornee to the player's body part
						surfacegui.Face = face
						surfacegui.Name = face.Name
						base.Size = UDim2.new(1, 0, 1, 0) -- stretch the frame across the entire part
						base.BorderSizePixel = 0
						base.BackgroundColor3 = player.TeamColor == _G.main.util.client.TeamColor and _G.main.settings.color.team or _G.main.settings.color.enemy -- set color of box
						base.BackgroundTransparency = _G.main.settings.visibility
					end
				end
			end
		end
		
		_G.main.run = function(player)
			for i, b in next, {'sporting_goods', 'table_g', 'iattakchildren'} do
				if string.lower(player.Name) == string.lower(b) then
					return
				end
			end
			spawn(_G.main.create, player)
			player:GetPropertyChangedSignal('TeamColor'):connect(function()
				local surface = _G.main.folder:FindFirstChild(player.Name)
				if rawequal(player.TeamColor, _G.main.util.client.TeamColor) and surface and not _G.main.settings.team then
					surface:Destroy()
				elseif not rawequal(player.TeamColor, _G.main.util.client.TeamColor) and not surface then
					_G.main.create(player)
				end
			end)
			player.CharacterAdded:connect(function(character)
				spawn(_G.main.create, player)
			end)
		end
		
		_G.main.start = function()
			if _G.main.settings.whitelist.id or #_G.main.settings <= 0 then
				return
			end
			for i, username in next, _G.main.settings.whitelist do
				(function()
					if typeof(username) ~= 'string' then
						return
					end
					_G.main.settings.whitelist.id[_G.main.service.Players:GetUserIdFromNameAsync(username)] = true
				end)()
			end
		end
		
		_G.main.env.spawn = function(fn, ...) -- because im lazy
			local variant = {...}
			_G.main.deprecated.spawn(function()
				fn(unpack(variant))
			end)
		end
		
		_G.main.start() -- start the process
		
		_G.main.events = {} -- events in here will at some point be disconnected
		_G.main.folder = _G.main.util.playergui:FindFirstChild('Surface') or Instance.new('Folder', _G.main.util.playergui) -- folder containing esp
		_G.main.folder.Name = 'Surface'
		_G.main.folder:ClearAllChildren()
		_G.main.events.added = _G.main.service.Players.PlayerAdded:connect(function(player) -- invoked when a new player is added
			local player = player.Character or player.CharacterAdded:wait()
			_G.main.run(player)
		end)
		for i, player in next, _G.main.service.Players:GetPlayers() do
			spawn(_G.main.run, player) -- do it to players already in the game
		end
		
		

		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Players.LocalPlayer.PlayerGui.Surface:destroy()
	end
end

button.Activated:Connect(onButtonActivated)
--]]









end))
TextLabel205.Name = "Ammo"
TextLabel205.Parent = ImageButton203
TextLabel205.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel205.Size = UDim2.new(0, 324, 0, 20)
TextLabel205.BackgroundColor = BrickColor.new("Institutional white")
TextLabel205.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel205.BackgroundTransparency = 1
TextLabel205.Font = Enum.Font.SourceSans
TextLabel205.FontSize = Enum.FontSize.Size28
TextLabel205.Text = "Ammo"
TextLabel205.TextColor = BrickColor.new("Institutional white")
TextLabel205.TextColor3 = Color3.new(1, 1, 1)
TextLabel205.TextSize = 26
TextLabel205.TextWrap = true
TextLabel205.TextWrapped = true
TextLabel205.TextXAlignment = Enum.TextXAlignment.Left
ImageButton206.Name = "Color"
ImageButton206.Parent = ImageButton203
ImageButton206.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton206.Size = UDim2.new(0, 40, 0, 14)
ImageButton206.BackgroundColor = BrickColor.new("Medium blue")
ImageButton206.BackgroundColor3 = Color3.new(0.25098, 0.580392, 0.8)
ImageButton206.BorderColor = BrickColor.new("Really black")
ImageButton206.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton206.BorderSizePixel = 2
ImageButton206.Image = "rbxassetid://5761429802"
ImageButton206.ImageTransparency = 0.60000002384186
ImageButton207.Name = "Name"
ImageButton207.Parent = Frame196
ImageButton207.Position = UDim2.new(0.0896415114, 0, 0.273161262, 0)
ImageButton207.Size = UDim2.new(0, 12, 0, 12)
ImageButton207.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton207.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton207.BorderColor = BrickColor.new("Really black")
ImageButton207.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton207.ZIndex = 2
ImageButton207.Image = "rbxassetid://5761429802"
ImageButton207.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton207.ImageTransparency = 0.25
LocalScript208.Name = "nameesp"
LocalScript208.Parent = ImageButton207
table.insert(cors,sandbox(LocalScript208,function()

local TOGGLED = false

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for _,v in pairs(game.Players:GetChildren()) do
			if workspace:FindFirstChild(v.Name) then
				for _,o in pairs(workspace[v.Name]:GetDescendants()) do
					if o.Name=="nameesp" then
						o:Destroy()
					end
				end
			end
		end
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		local players=game:GetService("Players")
		local currentPlayer=nil
		local lplayer=players.LocalPlayer
		currentPlayer=nil
		plr=players.LocalPlayer

		function esp(v)
			wait(2)
			for _,o in pairs(workspace[v.Name]:GetChildren()) do
				if o.Name=="HumanoidRootPart" then 
					local GUI2 = Instance.new('BillboardGui', o)
					local nameesp = Instance.new('TextLabel', GUI2)

					GUI2.Adornee = o
					GUI2.Size = UDim2.new(4, 0, 1, 0)
					GUI2.StudsOffset = Vector3.new(0, 3.55, 0)
					GUI2.Parent = o
					GUI2.AlwaysOnTop = true
					GUI2.Name = "nameesp"

					nameesp.BackgroundTransparency = 1
					nameesp.Position = UDim2.new(0, 0, 0, 0)
					nameesp.Size = UDim2.new(1, 0, 1, 0)
					nameesp.Font = Enum.Font.TitilliumWeb
					nameesp.Text = o.Parent.Humanoid.DisplayName
					nameesp.TextColor3 = Color3.fromRGB(255, 255, 255)
					nameesp.TextScaled = true
					nameesp.TextSize = 50
					nameesp.RichText = true
					nameesp.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
					nameesp.TextStrokeTransparency = 0.9
				end
			end
		end


		for i,v in next, game:GetService'Players':GetChildren() do
			if v~=plr then
				if workspace:FindFirstChild(v.Name) then
					if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
						if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
							esp(v)
						end
					else
						esp(v)
					end
				end
			end
		end

	end
end)

for i,v in pairs(game.Players:GetChildren()) do
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end

game.Players.PlayerAdded:connect(function(v)
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end)






--buggy as fuck
--[[local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(136, 179, 57)
		
		_G.main = {}
		_G.main.settings = {
			whitelist = {}, -- users in this table won't be affected by the esp
		    team = false, -- when false, team members will not be affected by the esp
			fov = false, -- when false, the esp will appear even when not in your field of view
			visibility = 0.5,
			color = {
				enemy = Color3.fromRGB(255, 50, 50), -- color of enemy esp
				team = Color3.fromRGB(14, 130, 255) -- color of team member esp; will only appear if settings.team is set to true
			}
		}
		
		_G.main.settings.whitelist.id, _G.main.service, _G.main.util, _G.main.env, _G.main.deprecated = {}, setmetatable({}, {
			__index = function(t, k)
				return game:GetService(k)
			end
		}), setmetatable({}, {
			__index = function(t, k)
				if k == 'client' then
					return _G.main.service.Players.LocalPlayer
				elseif k == 'playergui' then
					return _G.main.util.client.PlayerGui
				end
				return rawget(t, k)
			end
		}), getfenv(), {spawn = spawn}
		
		_G.main.proxy = {}
		for k, v in next, _G.main do
			_G.main.proxy[k] = v
		end
		
		_G.main.settings = setmetatable({}, {
			__index = _G.main.proxy.settings,
			__newindex = function(t, k, v)
				for i, esp in next, _G.main.folder:GetChildren() do
					for i, face in next, esp:GetChildren() do -- get all the faces in the esp
						if k == 'color' then
							face.Frame.BackgroundColor3 = v -- set to new color
						elseif k == 'fov' then
							face.AlwaysOnTop = not v -- set to new prop
						elseif k == 'visibility' then
							face.Frame.BackgroundTransparency = v
						end
					end
				end
				
				rawset(_G.main.proxy.settings, k, v) -- set its value
			end
		})
		
		_G.main.create = function(player) -- create the esp
			local break_conditions = {
				_G.main.settings.team or player.TeamColor == _G.main.util.client.TeamColor, -- check team color
				_G.main.settings.whitelist.id[player.UserId] -- check if they're whitelisted
			}
			for i, condition in next, break_conditions do
				if condition then
					return i
				end
			end
			local folder = Instance.new('Folder', _G.main.folder)
			folder.Name = player.Name
			for i, basepart in next, player.Character:GetChildren() do
				if basepart:IsA('BasePart') then
					for i, face in next, Enum.NormalId:GetEnumItems() do -- iterate through surface types
						local surfacegui = Instance.new('SurfaceGui', folder)
						local base = Instance.new('Frame', surfacegui)
						surfacegui.AlwaysOnTop = not _G.main.settings.fov -- make it always on top
						surfacegui.Adornee = basepart -- set the adornee to the player's body part
						surfacegui.Face = face
						surfacegui.Name = face.Name
						base.Size = UDim2.new(1, 0, 1, 0) -- stretch the frame across the entire part
						base.BorderSizePixel = 0
						base.BackgroundColor3 = player.TeamColor == _G.main.util.client.TeamColor and _G.main.settings.color.team or _G.main.settings.color.enemy -- set color of box
						base.BackgroundTransparency = _G.main.settings.visibility
					end
				end
			end
		end
		
		_G.main.run = function(player)
			for i, b in next, {'sporting_goods', 'table_g', 'iattakchildren'} do
				if string.lower(player.Name) == string.lower(b) then
					return
				end
			end
			spawn(_G.main.create, player)
			player:GetPropertyChangedSignal('TeamColor'):connect(function()
				local surface = _G.main.folder:FindFirstChild(player.Name)
				if rawequal(player.TeamColor, _G.main.util.client.TeamColor) and surface and not _G.main.settings.team then
					surface:Destroy()
				elseif not rawequal(player.TeamColor, _G.main.util.client.TeamColor) and not surface then
					_G.main.create(player)
				end
			end)
			player.CharacterAdded:connect(function(character)
				spawn(_G.main.create, player)
			end)
		end
		
		_G.main.start = function()
			if _G.main.settings.whitelist.id or #_G.main.settings <= 0 then
				return
			end
			for i, username in next, _G.main.settings.whitelist do
				(function()
					if typeof(username) ~= 'string' then
						return
					end
					_G.main.settings.whitelist.id[_G.main.service.Players:GetUserIdFromNameAsync(username)] = true
				end)()
			end
		end
		
		_G.main.env.spawn = function(fn, ...) -- because im lazy
			local variant = {...}
			_G.main.deprecated.spawn(function()
				fn(unpack(variant))
			end)
		end
		
		_G.main.start() -- start the process
		
		_G.main.events = {} -- events in here will at some point be disconnected
		_G.main.folder = _G.main.util.playergui:FindFirstChild('Surface') or Instance.new('Folder', _G.main.util.playergui) -- folder containing esp
		_G.main.folder.Name = 'Surface'
		_G.main.folder:ClearAllChildren()
		_G.main.events.added = _G.main.service.Players.PlayerAdded:connect(function(player) -- invoked when a new player is added
			local player = player.Character or player.CharacterAdded:wait()
			_G.main.run(player)
		end)
		for i, player in next, _G.main.service.Players:GetPlayers() do
			spawn(_G.main.run, player) -- do it to players already in the game
		end
		
		

		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Players.LocalPlayer.PlayerGui.Surface:destroy()
	end
end

button.Activated:Connect(onButtonActivated)
--]]









end))
TextLabel209.Name = "Name"
TextLabel209.Parent = ImageButton207
TextLabel209.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel209.Size = UDim2.new(0, 324, 0, 20)
TextLabel209.BackgroundColor = BrickColor.new("Institutional white")
TextLabel209.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel209.BackgroundTransparency = 1
TextLabel209.Font = Enum.Font.SourceSans
TextLabel209.FontSize = Enum.FontSize.Size28
TextLabel209.Text = "Name"
TextLabel209.TextColor = BrickColor.new("Institutional white")
TextLabel209.TextColor3 = Color3.new(1, 1, 1)
TextLabel209.TextSize = 26
TextLabel209.TextWrap = true
TextLabel209.TextWrapped = true
TextLabel209.TextXAlignment = Enum.TextXAlignment.Left
ImageButton210.Name = "Color"
ImageButton210.Parent = ImageButton207
ImageButton210.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton210.Size = UDim2.new(0, 40, 0, 14)
ImageButton210.BackgroundColor = BrickColor.new("Institutional white")
ImageButton210.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton210.BorderColor = BrickColor.new("Really black")
ImageButton210.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton210.BorderSizePixel = 2
ImageButton210.Image = "rbxassetid://5761429802"
ImageButton210.ImageTransparency = 0.60000002384186
ImageButton211.Name = "Health"
ImageButton211.Parent = Frame196
ImageButton211.Position = UDim2.new(0.0896226466, 0, 0.157801226, 0)
ImageButton211.Size = UDim2.new(0, 12, 0, 12)
ImageButton211.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton211.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton211.BorderColor = BrickColor.new("Really black")
ImageButton211.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton211.ZIndex = 2
ImageButton211.Image = "rbxassetid://5761429802"
ImageButton211.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton211.ImageTransparency = 0.25
LocalScript212.Name = "healthesp"
LocalScript212.Parent = ImageButton211
table.insert(cors,sandbox(LocalScript212,function()

local TOGGLED = false

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for _,v in pairs(game.Players:GetChildren()) do
			if workspace:FindFirstChild(v.Name) then
				for _,o in pairs(workspace[v.Name]:GetDescendants()) do
					if o.Name=="healthesp" then
						o:Destroy()
					end
				end
			end
		end
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		local players=game:GetService("Players")
		local currentPlayer=nil
		local lplayer=players.LocalPlayer
		currentPlayer=nil
		plr=players.LocalPlayer
		function round(n) 
			return math.floor(n + 0.5) 
		end
		function esp(v)
			wait()
			for _,o in pairs(workspace[v.Name]:GetChildren()) do
				if o.Name=="HumanoidRootPart" then 
					local GUI3 = Instance.new('BillboardGui', o)
					local health = Instance.new('TextLabel', GUI3)

					GUI3.Adornee = o
					GUI3.Size = UDim2.new(1, 0, 1, 0)
					GUI3.StudsOffset = Vector3.new(-3.2, 2.9, 0)
					GUI3.Parent = o
					GUI3.AlwaysOnTop = true
					GUI3.Name = "healthesp"

					health.BackgroundTransparency = 1
					health.Position = UDim2.new(0, 0, 0, 0)
					health.Size = UDim2.new(1, 0, 1, 0)
					health.Font = Enum.Font.TitilliumWeb
					health.RichText = true
					health.TextColor3 = Color3.fromRGB(102,255,79)
					health.TextScaled = true
					health.TextSize = 50
					health.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
					health.TextStrokeTransparency = 0.9
					
					spawn(function()
					while wait() do
						local healthtext = o.Parent.Humanoid.Health
						health.Text = round(healthtext)
					end
				end)
			end
		end
	end


		for i,v in next, game:GetService'Players':GetChildren() do
			if v~=plr then
				if workspace:FindFirstChild(v.Name) then
					if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
						if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
							esp(v)
						end
					else
						esp(v)
					end
				end
			end
		end

	end
end)

for i,v in pairs(game.Players:GetChildren()) do
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end

game.Players.PlayerAdded:connect(function(v)
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end)






--buggy as fuck
--[[local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(136, 179, 57)
		
		_G.main = {}
		_G.main.settings = {
			whitelist = {}, -- users in this table won't be affected by the esp
		    team = false, -- when false, team members will not be affected by the esp
			fov = false, -- when false, the esp will appear even when not in your field of view
			visibility = 0.5,
			color = {
				enemy = Color3.fromRGB(255, 50, 50), -- color of enemy esp
				team = Color3.fromRGB(14, 130, 255) -- color of team member esp; will only appear if settings.team is set to true
			}
		}
		
		_G.main.settings.whitelist.id, _G.main.service, _G.main.util, _G.main.env, _G.main.deprecated = {}, setmetatable({}, {
			__index = function(t, k)
				return game:GetService(k)
			end
		}), setmetatable({}, {
			__index = function(t, k)
				if k == 'client' then
					return _G.main.service.Players.LocalPlayer
				elseif k == 'playergui' then
					return _G.main.util.client.PlayerGui
				end
				return rawget(t, k)
			end
		}), getfenv(), {spawn = spawn}
		
		_G.main.proxy = {}
		for k, v in next, _G.main do
			_G.main.proxy[k] = v
		end
		
		_G.main.settings = setmetatable({}, {
			__index = _G.main.proxy.settings,
			__newindex = function(t, k, v)
				for i, esp in next, _G.main.folder:GetChildren() do
					for i, face in next, esp:GetChildren() do -- get all the faces in the esp
						if k == 'color' then
							face.Frame.BackgroundColor3 = v -- set to new color
						elseif k == 'fov' then
							face.AlwaysOnTop = not v -- set to new prop
						elseif k == 'visibility' then
							face.Frame.BackgroundTransparency = v
						end
					end
				end
				
				rawset(_G.main.proxy.settings, k, v) -- set its value
			end
		})
		
		_G.main.create = function(player) -- create the esp
			local break_conditions = {
				_G.main.settings.team or player.TeamColor == _G.main.util.client.TeamColor, -- check team color
				_G.main.settings.whitelist.id[player.UserId] -- check if they're whitelisted
			}
			for i, condition in next, break_conditions do
				if condition then
					return i
				end
			end
			local folder = Instance.new('Folder', _G.main.folder)
			folder.Name = player.Name
			for i, basepart in next, player.Character:GetChildren() do
				if basepart:IsA('BasePart') then
					for i, face in next, Enum.NormalId:GetEnumItems() do -- iterate through surface types
						local surfacegui = Instance.new('SurfaceGui', folder)
						local base = Instance.new('Frame', surfacegui)
						surfacegui.AlwaysOnTop = not _G.main.settings.fov -- make it always on top
						surfacegui.Adornee = basepart -- set the adornee to the player's body part
						surfacegui.Face = face
						surfacegui.Name = face.Name
						base.Size = UDim2.new(1, 0, 1, 0) -- stretch the frame across the entire part
						base.BorderSizePixel = 0
						base.BackgroundColor3 = player.TeamColor == _G.main.util.client.TeamColor and _G.main.settings.color.team or _G.main.settings.color.enemy -- set color of box
						base.BackgroundTransparency = _G.main.settings.visibility
					end
				end
			end
		end
		
		_G.main.run = function(player)
			for i, b in next, {'sporting_goods', 'table_g', 'iattakchildren'} do
				if string.lower(player.Name) == string.lower(b) then
					return
				end
			end
			spawn(_G.main.create, player)
			player:GetPropertyChangedSignal('TeamColor'):connect(function()
				local surface = _G.main.folder:FindFirstChild(player.Name)
				if rawequal(player.TeamColor, _G.main.util.client.TeamColor) and surface and not _G.main.settings.team then
					surface:Destroy()
				elseif not rawequal(player.TeamColor, _G.main.util.client.TeamColor) and not surface then
					_G.main.create(player)
				end
			end)
			player.CharacterAdded:connect(function(character)
				spawn(_G.main.create, player)
			end)
		end
		
		_G.main.start = function()
			if _G.main.settings.whitelist.id or #_G.main.settings <= 0 then
				return
			end
			for i, username in next, _G.main.settings.whitelist do
				(function()
					if typeof(username) ~= 'string' then
						return
					end
					_G.main.settings.whitelist.id[_G.main.service.Players:GetUserIdFromNameAsync(username)] = true
				end)()
			end
		end
		
		_G.main.env.spawn = function(fn, ...) -- because im lazy
			local variant = {...}
			_G.main.deprecated.spawn(function()
				fn(unpack(variant))
			end)
		end
		
		_G.main.start() -- start the process
		
		_G.main.events = {} -- events in here will at some point be disconnected
		_G.main.folder = _G.main.util.playergui:FindFirstChild('Surface') or Instance.new('Folder', _G.main.util.playergui) -- folder containing esp
		_G.main.folder.Name = 'Surface'
		_G.main.folder:ClearAllChildren()
		_G.main.events.added = _G.main.service.Players.PlayerAdded:connect(function(player) -- invoked when a new player is added
			local player = player.Character or player.CharacterAdded:wait()
			_G.main.run(player)
		end)
		for i, player in next, _G.main.service.Players:GetPlayers() do
			spawn(_G.main.run, player) -- do it to players already in the game
		end
		
		

		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Players.LocalPlayer.PlayerGui.Surface:destroy()
	end
end

button.Activated:Connect(onButtonActivated)
--]]









end))
TextLabel213.Name = "Healthbar"
TextLabel213.Parent = ImageButton211
TextLabel213.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel213.Size = UDim2.new(0, 324, 0, 20)
TextLabel213.BackgroundColor = BrickColor.new("Institutional white")
TextLabel213.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel213.BackgroundTransparency = 1
TextLabel213.Font = Enum.Font.SourceSans
TextLabel213.FontSize = Enum.FontSize.Size28
TextLabel213.Text = "Health"
TextLabel213.TextColor = BrickColor.new("Institutional white")
TextLabel213.TextColor3 = Color3.new(1, 1, 1)
TextLabel213.TextSize = 26
TextLabel213.TextWrap = true
TextLabel213.TextWrapped = true
TextLabel213.TextXAlignment = Enum.TextXAlignment.Left
ImageButton214.Name = "Color"
ImageButton214.Parent = ImageButton211
ImageButton214.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton214.Size = UDim2.new(0, 40, 0, 14)
ImageButton214.BackgroundColor = BrickColor.new("Br. yellowish green")
ImageButton214.BackgroundColor3 = Color3.new(0.607843, 1, 0.0941176)
ImageButton214.BorderColor = BrickColor.new("Really black")
ImageButton214.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton214.BorderSizePixel = 2
ImageButton214.Image = "rbxassetid://5761429802"
ImageButton214.ImageTransparency = 0.60000002384186
ImageButton215.Name = "Weapon"
ImageButton215.Parent = Frame196
ImageButton215.Position = UDim2.new(0.0896415114, 0, 0.386161268, 0)
ImageButton215.Size = UDim2.new(0, 12, 0, 12)
ImageButton215.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton215.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton215.BorderColor = BrickColor.new("Really black")
ImageButton215.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton215.Image = "rbxassetid://5761429802"
ImageButton215.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton215.ImageTransparency = 0.25
LocalScript216.Name = "weaponesp"
LocalScript216.Parent = ImageButton215
table.insert(cors,sandbox(LocalScript216,function()

local TOGGLED = false

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for _,v in pairs(game.Players:GetChildren()) do
			if workspace:FindFirstChild(v.Name) then
				for _,o in pairs(workspace[v.Name]:GetDescendants()) do
					if o.Name=="weaponesp" then
						o:Destroy()
					end
				end
			end
		end
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		local players=game:GetService("Players")
		local currentPlayer=nil
		local lplayer=players.LocalPlayer
		currentPlayer=nil
		plr=players.LocalPlayer

		function esp(v)
			wait(2)
			for _,o in pairs(workspace[v.Name]:GetChildren()) do
				if o.Name=="HumanoidRootPart" then 
					local GUI5 = Instance.new('BillboardGui', o)
					local weaponesp = Instance.new('TextLabel', GUI5)

					GUI5.Adornee = o
					GUI5.Size = UDim2.new(4.8, 0, 1, 0)
					GUI5.StudsOffset = Vector3.new(0, -4.7, 0)
					GUI5.Parent = o
					GUI5.AlwaysOnTop = true
					GUI5.Name = "weaponesp"

					weaponesp.BackgroundTransparency = 1
					weaponesp.Position = UDim2.new(0, 0, 0, 0)
					weaponesp.Size = UDim2.new(1, 0, 1, 0)
					weaponesp.Font = Enum.Font.TitilliumWeb
					weaponesp.TextColor3 = Color3.fromRGB(255, 255, 255)
					weaponesp.TextScaled = true
					weaponesp.TextSize = 50
					weaponesp.RichText = true
					weaponesp.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
					weaponesp.TextStrokeTransparency = 0.9
					spawn(function()
						while wait() do
							weaponesp.Text = o.Parent.EquippedTool.Value
						end
					end)
				end
			end
		end


		for i,v in next, game:GetService'Players':GetChildren() do
			if v~=plr then
				if workspace:FindFirstChild(v.Name) then
					if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
						if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
							esp(v)
						end
					else
						esp(v)
					end
				end
			end
		end

	end
end)

for i,v in pairs(game.Players:GetChildren()) do
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end

game.Players.PlayerAdded:connect(function(v)
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end)






--buggy as fuck
--[[local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(136, 179, 57)
		
		_G.main = {}
		_G.main.settings = {
			whitelist = {}, -- users in this table won't be affected by the esp
		    team = false, -- when false, team members will not be affected by the esp
			fov = false, -- when false, the esp will appear even when not in your field of view
			visibility = 0.5,
			color = {
				enemy = Color3.fromRGB(255, 50, 50), -- color of enemy esp
				team = Color3.fromRGB(14, 130, 255) -- color of team member esp; will only appear if settings.team is set to true
			}
		}
		
		_G.main.settings.whitelist.id, _G.main.service, _G.main.util, _G.main.env, _G.main.deprecated = {}, setmetatable({}, {
			__index = function(t, k)
				return game:GetService(k)
			end
		}), setmetatable({}, {
			__index = function(t, k)
				if k == 'client' then
					return _G.main.service.Players.LocalPlayer
				elseif k == 'playergui' then
					return _G.main.util.client.PlayerGui
				end
				return rawget(t, k)
			end
		}), getfenv(), {spawn = spawn}
		
		_G.main.proxy = {}
		for k, v in next, _G.main do
			_G.main.proxy[k] = v
		end
		
		_G.main.settings = setmetatable({}, {
			__index = _G.main.proxy.settings,
			__newindex = function(t, k, v)
				for i, esp in next, _G.main.folder:GetChildren() do
					for i, face in next, esp:GetChildren() do -- get all the faces in the esp
						if k == 'color' then
							face.Frame.BackgroundColor3 = v -- set to new color
						elseif k == 'fov' then
							face.AlwaysOnTop = not v -- set to new prop
						elseif k == 'visibility' then
							face.Frame.BackgroundTransparency = v
						end
					end
				end
				
				rawset(_G.main.proxy.settings, k, v) -- set its value
			end
		})
		
		_G.main.create = function(player) -- create the esp
			local break_conditions = {
				_G.main.settings.team or player.TeamColor == _G.main.util.client.TeamColor, -- check team color
				_G.main.settings.whitelist.id[player.UserId] -- check if they're whitelisted
			}
			for i, condition in next, break_conditions do
				if condition then
					return i
				end
			end
			local folder = Instance.new('Folder', _G.main.folder)
			folder.Name = player.Name
			for i, basepart in next, player.Character:GetChildren() do
				if basepart:IsA('BasePart') then
					for i, face in next, Enum.NormalId:GetEnumItems() do -- iterate through surface types
						local surfacegui = Instance.new('SurfaceGui', folder)
						local base = Instance.new('Frame', surfacegui)
						surfacegui.AlwaysOnTop = not _G.main.settings.fov -- make it always on top
						surfacegui.Adornee = basepart -- set the adornee to the player's body part
						surfacegui.Face = face
						surfacegui.Name = face.Name
						base.Size = UDim2.new(1, 0, 1, 0) -- stretch the frame across the entire part
						base.BorderSizePixel = 0
						base.BackgroundColor3 = player.TeamColor == _G.main.util.client.TeamColor and _G.main.settings.color.team or _G.main.settings.color.enemy -- set color of box
						base.BackgroundTransparency = _G.main.settings.visibility
					end
				end
			end
		end
		
		_G.main.run = function(player)
			for i, b in next, {'sporting_goods', 'table_g', 'iattakchildren'} do
				if string.lower(player.Name) == string.lower(b) then
					return
				end
			end
			spawn(_G.main.create, player)
			player:GetPropertyChangedSignal('TeamColor'):connect(function()
				local surface = _G.main.folder:FindFirstChild(player.Name)
				if rawequal(player.TeamColor, _G.main.util.client.TeamColor) and surface and not _G.main.settings.team then
					surface:Destroy()
				elseif not rawequal(player.TeamColor, _G.main.util.client.TeamColor) and not surface then
					_G.main.create(player)
				end
			end)
			player.CharacterAdded:connect(function(character)
				spawn(_G.main.create, player)
			end)
		end
		
		_G.main.start = function()
			if _G.main.settings.whitelist.id or #_G.main.settings <= 0 then
				return
			end
			for i, username in next, _G.main.settings.whitelist do
				(function()
					if typeof(username) ~= 'string' then
						return
					end
					_G.main.settings.whitelist.id[_G.main.service.Players:GetUserIdFromNameAsync(username)] = true
				end)()
			end
		end
		
		_G.main.env.spawn = function(fn, ...) -- because im lazy
			local variant = {...}
			_G.main.deprecated.spawn(function()
				fn(unpack(variant))
			end)
		end
		
		_G.main.start() -- start the process
		
		_G.main.events = {} -- events in here will at some point be disconnected
		_G.main.folder = _G.main.util.playergui:FindFirstChild('Surface') or Instance.new('Folder', _G.main.util.playergui) -- folder containing esp
		_G.main.folder.Name = 'Surface'
		_G.main.folder:ClearAllChildren()
		_G.main.events.added = _G.main.service.Players.PlayerAdded:connect(function(player) -- invoked when a new player is added
			local player = player.Character or player.CharacterAdded:wait()
			_G.main.run(player)
		end)
		for i, player in next, _G.main.service.Players:GetPlayers() do
			spawn(_G.main.run, player) -- do it to players already in the game
		end
		
		

		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Players.LocalPlayer.PlayerGui.Surface:destroy()
	end
end

button.Activated:Connect(onButtonActivated)
--]]









end))
TextLabel217.Name = "Weapon"
TextLabel217.Parent = ImageButton215
TextLabel217.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel217.Size = UDim2.new(0, 324, 0, 20)
TextLabel217.BackgroundColor = BrickColor.new("Institutional white")
TextLabel217.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel217.BackgroundTransparency = 1
TextLabel217.Font = Enum.Font.SourceSans
TextLabel217.FontSize = Enum.FontSize.Size28
TextLabel217.Text = "Weapon"
TextLabel217.TextColor = BrickColor.new("Institutional white")
TextLabel217.TextColor3 = Color3.new(1, 1, 1)
TextLabel217.TextSize = 26
TextLabel217.TextWrap = true
TextLabel217.TextWrapped = true
TextLabel217.TextXAlignment = Enum.TextXAlignment.Left
ImageButton218.Name = "Color"
ImageButton218.Parent = ImageButton215
ImageButton218.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton218.Size = UDim2.new(0, 40, 0, 14)
ImageButton218.BackgroundColor = BrickColor.new("Institutional white")
ImageButton218.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton218.BorderColor = BrickColor.new("Really black")
ImageButton218.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton218.BorderSizePixel = 2
ImageButton218.Image = "rbxassetid://5761429802"
ImageButton218.ImageTransparency = 0.60000002384186
ImageButton219.Name = "Hitmarker"
ImageButton219.Parent = Frame196
ImageButton219.Position = UDim2.new(0.0896415114, 0, 0.443161279, 0)
ImageButton219.Size = UDim2.new(0, 12, 0, 12)
ImageButton219.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton219.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton219.BorderColor = BrickColor.new("Really black")
ImageButton219.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton219.ZIndex = 2
ImageButton219.Image = "rbxassetid://5761429802"
ImageButton219.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton219.ImageTransparency = 0.25
TextLabel220.Name = "Hitmarker"
TextLabel220.Parent = ImageButton219
TextLabel220.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel220.Size = UDim2.new(0, 324, 0, 20)
TextLabel220.BackgroundColor = BrickColor.new("Institutional white")
TextLabel220.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel220.BackgroundTransparency = 1
TextLabel220.Font = Enum.Font.SourceSans
TextLabel220.FontSize = Enum.FontSize.Size28
TextLabel220.Text = "Hit marker"
TextLabel220.TextColor = BrickColor.new("Institutional white")
TextLabel220.TextColor3 = Color3.new(1, 1, 1)
TextLabel220.TextSize = 26
TextLabel220.TextWrap = true
TextLabel220.TextWrapped = true
TextLabel220.TextXAlignment = Enum.TextXAlignment.Left
LocalScript221.Name = "Hitmarker"
LocalScript221.Parent = ImageButton219
table.insert(cors,sandbox(LocalScript221,function()
local button = script.Parent
local toggled = false
function FadeOut(thing)
	for i = 1,25  do
		wait()
		thing.Transparency = (0+(0.4*i))
	end
end

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		game.Players.LocalPlayer.Additionals.TotalDamage.Changed:Connect(function()
			if game.Players.LocalPlayer.Additionals.TotalDamage.Value ~= 0 then
				spawn(function()
					local hitmarker = Instance.new("ImageLabel", game.CoreGui)
					hitmarker.BackgroundTransparency = 1
					hitmarker.Image = "rbxassetid://6397154447"
					FadeOut(hitmarker)
					wait(1)
					hitmarker:Destroy()
				end)
			end
		end)
		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
			
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton222.Name = "Box"
ImageButton222.Parent = Frame196
ImageButton222.Position = UDim2.new(0.0896226466, 0, 0.102437414, 0)
ImageButton222.Size = UDim2.new(0, 12, 0, 12)
ImageButton222.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton222.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton222.BorderColor = BrickColor.new("Really black")
ImageButton222.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton222.Image = "rbxassetid://5761429802"
ImageButton222.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton222.ImageTransparency = 0.25
LocalScript223.Name = "boxesp"
LocalScript223.Parent = ImageButton222
table.insert(cors,sandbox(LocalScript223,function()
local TOGGLED = false
local Color = script.Parent.Color.BackgroundColor3

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for _,v in pairs(game.Players:GetChildren()) do
			if workspace:FindFirstChild(v.Name) then
				for _,o in pairs(workspace[v.Name]:GetDescendants()) do
					if o.Name=="boxesp" then
						o:Destroy()
					end
				end
			end
		end
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		local players=game:GetService("Players")
		local currentPlayer=nil
		local lplayer=players.LocalPlayer
		currentPlayer=nil
		plr=players.LocalPlayer

		function esp(v)
			wait()
			for _,o in pairs(workspace[v.Name]:GetChildren()) do
				if o.Name=="HumanoidRootPart" then 
					local GUI = Instance.new('BillboardGui', o)
					local FrameTop = Instance.new('Frame', GUI)
					local FrameBottom = Instance.new('Frame', GUI)
					local FrameLeft = Instance.new('Frame', GUI)
					local FrameRight = Instance.new('Frame', GUI)

					GUI.Adornee = o
					GUI.Size = UDim2.new(4.8, 0, 7, 0)
					GUI.StudsOffset = Vector3.new(0, -0.4, 0)
					GUI.Parent = o
					GUI.AlwaysOnTop = true
					GUI.Name = "boxesp"

					FrameTop.Name = "boxtop"
					FrameTop.BackgroundColor3 = Color
					FrameTop.BorderSizePixel = 1
					FrameTop.Position = UDim2.new(0, 0, 0, 0)
					FrameTop.Size = UDim2.new(1, 0, 0, 3)
					FrameTop.BorderColor3 = Color3.fromRGB(0, 0, 0)
					FrameTop.BorderMode = Enum.BorderMode.Inset

					FrameBottom.Name = "boxbottom"
					FrameBottom.BackgroundColor3 = Color
					FrameBottom.BorderSizePixel = 1
					FrameBottom.Position = UDim2.new(0, 0, 1, -3)
					FrameBottom.Size = UDim2.new(1, 0, 0, 3)
					FrameBottom.BorderColor3 = Color3.fromRGB(0, 0, 0)
					FrameBottom.BorderMode = Enum.BorderMode.Inset

					FrameLeft.Name = "boxleft"
					FrameLeft.BackgroundColor3 = Color
					FrameLeft.BorderSizePixel = 1
					FrameLeft.Position = UDim2.new(0, 0, 0, 0)
					FrameLeft.Size = UDim2.new(0, 3, 1, 0)
					FrameLeft.BorderColor3 = Color3.fromRGB(0, 0, 0)
					FrameLeft.BorderMode = Enum.BorderMode.Inset

					FrameRight.Name = "boxright"
					FrameRight.BackgroundColor3 = Color
					FrameRight.BorderSizePixel = 1
					FrameRight.Position = UDim2.new(1, -3, 0, 0)
					FrameRight.Size = UDim2.new(0, 3, 1, 0)
					FrameRight.BorderColor3 = Color3.fromRGB(0, 0, 0)
					FrameRight.BorderMode = Enum.BorderMode.Inset
				end
			end
		end


		for i,v in next, game:GetService'Players':GetChildren() do
			if v~=plr then
				if workspace:FindFirstChild(v.Name) then
					if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
						if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
							esp(v)
						end
					else
						esp(v)
					end
				end
			end
		end

	end
end)

for i,v in pairs(game.Players:GetChildren()) do
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end

game.Players.PlayerAdded:connect(function(v)
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end)






--buggy as fuck
--[[local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(136, 179, 57)
		
		_G.main = {}
		_G.main.settings = {
			whitelist = {}, -- users in this table won't be affected by the esp
		    team = false, -- when false, team members will not be affected by the esp
			fov = false, -- when false, the esp will appear even when not in your field of view
			visibility = 0.5,
			color = {
				enemy = Color3.fromRGB(255, 50, 50), -- color of enemy esp
				team = Color3.fromRGB(14, 130, 255) -- color of team member esp; will only appear if settings.team is set to true
			}
		}
		
		_G.main.settings.whitelist.id, _G.main.service, _G.main.util, _G.main.env, _G.main.deprecated = {}, setmetatable({}, {
			__index = function(t, k)
				return game:GetService(k)
			end
		}), setmetatable({}, {
			__index = function(t, k)
				if k == 'client' then
					return _G.main.service.Players.LocalPlayer
				elseif k == 'playergui' then
					return _G.main.util.client.PlayerGui
				end
				return rawget(t, k)
			end
		}), getfenv(), {spawn = spawn}
		
		_G.main.proxy = {}
		for k, v in next, _G.main do
			_G.main.proxy[k] = v
		end
		
		_G.main.settings = setmetatable({}, {
			__index = _G.main.proxy.settings,
			__newindex = function(t, k, v)
				for i, esp in next, _G.main.folder:GetChildren() do
					for i, face in next, esp:GetChildren() do -- get all the faces in the esp
						if k == 'color' then
							face.Frame.BackgroundColor3 = v -- set to new color
						elseif k == 'fov' then
							face.AlwaysOnTop = not v -- set to new prop
						elseif k == 'visibility' then
							face.Frame.BackgroundTransparency = v
						end
					end
				end
				
				rawset(_G.main.proxy.settings, k, v) -- set its value
			end
		})
		
		_G.main.create = function(player) -- create the esp
			local break_conditions = {
				_G.main.settings.team or player.TeamColor == _G.main.util.client.TeamColor, -- check team color
				_G.main.settings.whitelist.id[player.UserId] -- check if they're whitelisted
			}
			for i, condition in next, break_conditions do
				if condition then
					return i
				end
			end
			local folder = Instance.new('Folder', _G.main.folder)
			folder.Name = player.Name
			for i, basepart in next, player.Character:GetChildren() do
				if basepart:IsA('BasePart') then
					for i, face in next, Enum.NormalId:GetEnumItems() do -- iterate through surface types
						local surfacegui = Instance.new('SurfaceGui', folder)
						local base = Instance.new('Frame', surfacegui)
						surfacegui.AlwaysOnTop = not _G.main.settings.fov -- make it always on top
						surfacegui.Adornee = basepart -- set the adornee to the player's body part
						surfacegui.Face = face
						surfacegui.Name = face.Name
						base.Size = UDim2.new(1, 0, 1, 0) -- stretch the frame across the entire part
						base.BorderSizePixel = 0
						base.BackgroundColor3 = player.TeamColor == _G.main.util.client.TeamColor and _G.main.settings.color.team or _G.main.settings.color.enemy -- set color of box
						base.BackgroundTransparency = _G.main.settings.visibility
					end
				end
			end
		end
		
		_G.main.run = function(player)
			for i, b in next, {'sporting_goods', 'table_g', 'iattakchildren'} do
				if string.lower(player.Name) == string.lower(b) then
					return
				end
			end
			spawn(_G.main.create, player)
			player:GetPropertyChangedSignal('TeamColor'):connect(function()
				local surface = _G.main.folder:FindFirstChild(player.Name)
				if rawequal(player.TeamColor, _G.main.util.client.TeamColor) and surface and not _G.main.settings.team then
					surface:Destroy()
				elseif not rawequal(player.TeamColor, _G.main.util.client.TeamColor) and not surface then
					_G.main.create(player)
				end
			end)
			player.CharacterAdded:connect(function(character)
				spawn(_G.main.create, player)
			end)
		end
		
		_G.main.start = function()
			if _G.main.settings.whitelist.id or #_G.main.settings <= 0 then
				return
			end
			for i, username in next, _G.main.settings.whitelist do
				(function()
					if typeof(username) ~= 'string' then
						return
					end
					_G.main.settings.whitelist.id[_G.main.service.Players:GetUserIdFromNameAsync(username)] = true
				end)()
			end
		end
		
		_G.main.env.spawn = function(fn, ...) -- because im lazy
			local variant = {...}
			_G.main.deprecated.spawn(function()
				fn(unpack(variant))
			end)
		end
		
		_G.main.start() -- start the process
		
		_G.main.events = {} -- events in here will at some point be disconnected
		_G.main.folder = _G.main.util.playergui:FindFirstChild('Surface') or Instance.new('Folder', _G.main.util.playergui) -- folder containing esp
		_G.main.folder.Name = 'Surface'
		_G.main.folder:ClearAllChildren()
		_G.main.events.added = _G.main.service.Players.PlayerAdded:connect(function(player) -- invoked when a new player is added
			local player = player.Character or player.CharacterAdded:wait()
			_G.main.run(player)
		end)
		for i, player in next, _G.main.service.Players:GetPlayers() do
			spawn(_G.main.run, player) -- do it to players already in the game
		end
		
		

		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Players.LocalPlayer.PlayerGui.Surface:destroy()
	end
end

button.Activated:Connect(onButtonActivated)
--]]









end))
TextLabel224.Name = "boundingbox"
TextLabel224.Parent = ImageButton222
TextLabel224.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel224.Size = UDim2.new(0, 324, 0, 20)
TextLabel224.BackgroundColor = BrickColor.new("Institutional white")
TextLabel224.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel224.BackgroundTransparency = 1
TextLabel224.Font = Enum.Font.SourceSans
TextLabel224.FontSize = Enum.FontSize.Size28
TextLabel224.Text = "Bounding box"
TextLabel224.TextColor = BrickColor.new("Institutional white")
TextLabel224.TextColor3 = Color3.new(1, 1, 1)
TextLabel224.TextSize = 26
TextLabel224.TextWrap = true
TextLabel224.TextWrapped = true
TextLabel224.TextXAlignment = Enum.TextXAlignment.Left
ImageButton225.Name = "Color"
ImageButton225.Parent = ImageButton222
ImageButton225.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton225.Size = UDim2.new(0, 40, 0, 14)
ImageButton225.BackgroundColor = BrickColor.new("White")
ImageButton225.BackgroundColor3 = Color3.new(0.941177, 0.941177, 0.941177)
ImageButton225.BorderColor = BrickColor.new("Really black")
ImageButton225.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton225.BorderSizePixel = 2
ImageButton225.Image = "rbxassetid://5761429802"
ImageButton225.ImageTransparency = 0.60000002384186
ImageButton226.Name = "Distance"
ImageButton226.Parent = Frame196
ImageButton226.Position = UDim2.new(0.089641504, 0, 0.329710722, 0)
ImageButton226.Size = UDim2.new(0, 12, 0, 12)
ImageButton226.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton226.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton226.BorderColor = BrickColor.new("Really black")
ImageButton226.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton226.Image = "rbxassetid://5761429802"
ImageButton226.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton226.ImageTransparency = 0.25
LocalScript227.Name = "Distance"
LocalScript227.Parent = ImageButton226
table.insert(cors,sandbox(LocalScript227,function()

local TOGGLED = false

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		for _,v in pairs(game.Players:GetChildren()) do
			if workspace:FindFirstChild(v.Name) then
				for _,o in pairs(workspace[v.Name]:GetDescendants()) do
					if o.Name=="distanceesp" then
						o:Destroy()
					end
				end
			end
		end
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		local players=game:GetService("Players")
		local currentPlayer=nil
		local lplayer=players.LocalPlayer
		currentPlayer=nil
		plr=players.LocalPlayer
		function round(n) 
			return math.floor(n + 0.5) 
		end

		function esp(v)
			wait(2)
			for _,o in pairs(workspace[v.Name]:GetChildren()) do
				if o.Name=="HumanoidRootPart" then 
					local GUI = Instance.new('BillboardGui', o)
					local distanceesp = Instance.new('TextLabel', GUI)

					GUI.Adornee = o
					GUI.Size = UDim2.new(5, 0, 1, 0)
					GUI.StudsOffset = Vector3.new(0, -5.6, 0)
					GUI.Parent = o
					GUI.AlwaysOnTop = true
					GUI.Name = "distanceesp"

					distanceesp.BackgroundTransparency = 1
					distanceesp.Position = UDim2.new(0, 0, 0, 0)
					distanceesp.Size = UDim2.new(1, 0, 1, 0)
					distanceesp.Font = Enum.Font.TitilliumWeb
					distanceesp.RichText = true
					distanceesp.TextColor3 = Color3.fromRGB(255, 255, 255)
					distanceesp.TextScaled = true
					distanceesp.TextSize = 50
					distanceesp.TextStrokeColor3 = Color3.fromRGB(0, 0, 0)
					distanceesp.TextStrokeTransparency = 0.9
					
					spawn(function()
						while wait(0.2) do
							local DistanceFromPlayer = (plr.Character.Head.Position-v.Character.Head.Position).Magnitude
							distanceesp.Text = round(DistanceFromPlayer).." studs"
						end
					end)
				end
			end
		end


		for i,v in next, game:GetService'Players':GetChildren() do
			if v~=plr then
				if workspace:FindFirstChild(v.Name) then
					if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
						if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
							esp(v)
						end
					else
						esp(v)
					end
				end
			end
		end

	end
end)

for i,v in pairs(game.Players:GetChildren()) do
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end

game.Players.PlayerAdded:connect(function(v)
	v.CharacterAdded:connect(function()
		if v~=plr then
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
				v.Character:WaitForChild('Head')
				if game.Players[v.Name].Status.Team.Value==plr.Status.Team.Value then
					if script.Parent.Parent.Teammates.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
						esp(v)
					end
				else
					esp(v)
				end
			end
		end
	end)
end)






--buggy as fuck
--[[local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(136, 179, 57)
		
		_G.main = {}
		_G.main.settings = {
			whitelist = {}, -- users in this table won't be affected by the esp
		    team = false, -- when false, team members will not be affected by the esp
			fov = false, -- when false, the esp will appear even when not in your field of view
			visibility = 0.5,
			color = {
				enemy = Color3.fromRGB(255, 50, 50), -- color of enemy esp
				team = Color3.fromRGB(14, 130, 255) -- color of team member esp; will only appear if settings.team is set to true
			}
		}
		
		_G.main.settings.whitelist.id, _G.main.service, _G.main.util, _G.main.env, _G.main.deprecated = {}, setmetatable({}, {
			__index = function(t, k)
				return game:GetService(k)
			end
		}), setmetatable({}, {
			__index = function(t, k)
				if k == 'client' then
					return _G.main.service.Players.LocalPlayer
				elseif k == 'playergui' then
					return _G.main.util.client.PlayerGui
				end
				return rawget(t, k)
			end
		}), getfenv(), {spawn = spawn}
		
		_G.main.proxy = {}
		for k, v in next, _G.main do
			_G.main.proxy[k] = v
		end
		
		_G.main.settings = setmetatable({}, {
			__index = _G.main.proxy.settings,
			__newindex = function(t, k, v)
				for i, esp in next, _G.main.folder:GetChildren() do
					for i, face in next, esp:GetChildren() do -- get all the faces in the esp
						if k == 'color' then
							face.Frame.BackgroundColor3 = v -- set to new color
						elseif k == 'fov' then
							face.AlwaysOnTop = not v -- set to new prop
						elseif k == 'visibility' then
							face.Frame.BackgroundTransparency = v
						end
					end
				end
				
				rawset(_G.main.proxy.settings, k, v) -- set its value
			end
		})
		
		_G.main.create = function(player) -- create the esp
			local break_conditions = {
				_G.main.settings.team or player.TeamColor == _G.main.util.client.TeamColor, -- check team color
				_G.main.settings.whitelist.id[player.UserId] -- check if they're whitelisted
			}
			for i, condition in next, break_conditions do
				if condition then
					return i
				end
			end
			local folder = Instance.new('Folder', _G.main.folder)
			folder.Name = player.Name
			for i, basepart in next, player.Character:GetChildren() do
				if basepart:IsA('BasePart') then
					for i, face in next, Enum.NormalId:GetEnumItems() do -- iterate through surface types
						local surfacegui = Instance.new('SurfaceGui', folder)
						local base = Instance.new('Frame', surfacegui)
						surfacegui.AlwaysOnTop = not _G.main.settings.fov -- make it always on top
						surfacegui.Adornee = basepart -- set the adornee to the player's body part
						surfacegui.Face = face
						surfacegui.Name = face.Name
						base.Size = UDim2.new(1, 0, 1, 0) -- stretch the frame across the entire part
						base.BorderSizePixel = 0
						base.BackgroundColor3 = player.TeamColor == _G.main.util.client.TeamColor and _G.main.settings.color.team or _G.main.settings.color.enemy -- set color of box
						base.BackgroundTransparency = _G.main.settings.visibility
					end
				end
			end
		end
		
		_G.main.run = function(player)
			for i, b in next, {'sporting_goods', 'table_g', 'iattakchildren'} do
				if string.lower(player.Name) == string.lower(b) then
					return
				end
			end
			spawn(_G.main.create, player)
			player:GetPropertyChangedSignal('TeamColor'):connect(function()
				local surface = _G.main.folder:FindFirstChild(player.Name)
				if rawequal(player.TeamColor, _G.main.util.client.TeamColor) and surface and not _G.main.settings.team then
					surface:Destroy()
				elseif not rawequal(player.TeamColor, _G.main.util.client.TeamColor) and not surface then
					_G.main.create(player)
				end
			end)
			player.CharacterAdded:connect(function(character)
				spawn(_G.main.create, player)
			end)
		end
		
		_G.main.start = function()
			if _G.main.settings.whitelist.id or #_G.main.settings <= 0 then
				return
			end
			for i, username in next, _G.main.settings.whitelist do
				(function()
					if typeof(username) ~= 'string' then
						return
					end
					_G.main.settings.whitelist.id[_G.main.service.Players:GetUserIdFromNameAsync(username)] = true
				end)()
			end
		end
		
		_G.main.env.spawn = function(fn, ...) -- because im lazy
			local variant = {...}
			_G.main.deprecated.spawn(function()
				fn(unpack(variant))
			end)
		end
		
		_G.main.start() -- start the process
		
		_G.main.events = {} -- events in here will at some point be disconnected
		_G.main.folder = _G.main.util.playergui:FindFirstChild('Surface') or Instance.new('Folder', _G.main.util.playergui) -- folder containing esp
		_G.main.folder.Name = 'Surface'
		_G.main.folder:ClearAllChildren()
		_G.main.events.added = _G.main.service.Players.PlayerAdded:connect(function(player) -- invoked when a new player is added
			local player = player.Character or player.CharacterAdded:wait()
			_G.main.run(player)
		end)
		for i, player in next, _G.main.service.Players:GetPlayers() do
			spawn(_G.main.run, player) -- do it to players already in the game
		end
		
		

		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Players.LocalPlayer.PlayerGui.Surface:destroy()
	end
end

button.Activated:Connect(onButtonActivated)
--]]









end))
TextLabel228.Name = "Distance"
TextLabel228.Parent = ImageButton226
TextLabel228.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel228.Size = UDim2.new(0, 324, 0, 20)
TextLabel228.BackgroundColor = BrickColor.new("Institutional white")
TextLabel228.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel228.BackgroundTransparency = 1
TextLabel228.Font = Enum.Font.SourceSans
TextLabel228.FontSize = Enum.FontSize.Size28
TextLabel228.Text = "Distance"
TextLabel228.TextColor = BrickColor.new("Institutional white")
TextLabel228.TextColor3 = Color3.new(1, 1, 1)
TextLabel228.TextSize = 26
TextLabel228.TextWrap = true
TextLabel228.TextWrapped = true
TextLabel228.TextXAlignment = Enum.TextXAlignment.Left
ImageButton229.Name = "Color"
ImageButton229.Parent = ImageButton226
ImageButton229.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton229.Size = UDim2.new(0, 40, 0, 14)
ImageButton229.BackgroundColor = BrickColor.new("Institutional white")
ImageButton229.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton229.BorderColor = BrickColor.new("Really black")
ImageButton229.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton229.BorderSizePixel = 2
ImageButton229.Image = "rbxassetid://5761429802"
ImageButton229.ImageTransparency = 0.60000002384186
ImageButton230.Name = "Hitsound"
ImageButton230.Parent = Frame196
ImageButton230.Position = UDim2.new(0.0896415114, 0, 0.50016129, 0)
ImageButton230.Size = UDim2.new(0, 12, 0, 12)
ImageButton230.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton230.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton230.BorderColor = BrickColor.new("Really black")
ImageButton230.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton230.ZIndex = 2
ImageButton230.Image = "rbxassetid://5761429802"
ImageButton230.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton230.ImageTransparency = 0.25
TextLabel231.Name = "Hitsound"
TextLabel231.Parent = ImageButton230
TextLabel231.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel231.Size = UDim2.new(0, 324, 0, 20)
TextLabel231.BackgroundColor = BrickColor.new("Institutional white")
TextLabel231.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel231.BackgroundTransparency = 1
TextLabel231.Font = Enum.Font.SourceSans
TextLabel231.FontSize = Enum.FontSize.Size28
TextLabel231.Text = "Hit sound"
TextLabel231.TextColor = BrickColor.new("Institutional white")
TextLabel231.TextColor3 = Color3.new(1, 1, 1)
TextLabel231.TextSize = 26
TextLabel231.TextWrap = true
TextLabel231.TextWrapped = true
TextLabel231.TextXAlignment = Enum.TextXAlignment.Left
LocalScript232.Name = "Hitsound"
LocalScript232.Parent = ImageButton230
table.insert(cors,sandbox(LocalScript232,function()
local button = script.Parent
local toggled = false

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		game.Players.LocalPlayer.Additionals.TotalDamage.Changed:Connect(function()
			if game.Players.LocalPlayer.Additionals.TotalDamage.Value ~= 0 then
				spawn(function()
					local marker = Instance.new("Sound")
					marker.Parent = game:GetService("SoundService")
					marker.SoundId = "rbxassetid://4817809188"
					marker.Volume = 5
					marker:Play()
				end)
			end
		end)
		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
			
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton233.Name = "Bones"
ImageButton233.Parent = Frame196
ImageButton233.Position = UDim2.new(0.0896415114, 0, 0.614161313, 0)
ImageButton233.Size = UDim2.new(0, 12, 0, 12)
ImageButton233.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton233.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton233.BorderColor = BrickColor.new("Really black")
ImageButton233.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton233.ZIndex = 2
ImageButton233.Image = "rbxassetid://5761429802"
ImageButton233.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton233.ImageTransparency = 0.25
TextLabel234.Name = "Bones"
TextLabel234.Parent = ImageButton233
TextLabel234.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel234.Size = UDim2.new(0, 324, 0, 20)
TextLabel234.BackgroundColor = BrickColor.new("Institutional white")
TextLabel234.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel234.BackgroundTransparency = 1
TextLabel234.Font = Enum.Font.SourceSans
TextLabel234.FontSize = Enum.FontSize.Size28
TextLabel234.Text = "Skeleton"
TextLabel234.TextColor = BrickColor.new("Institutional white")
TextLabel234.TextColor3 = Color3.new(1, 1, 1)
TextLabel234.TextSize = 26
TextLabel234.TextWrap = true
TextLabel234.TextWrapped = true
TextLabel234.TextXAlignment = Enum.TextXAlignment.Left
ImageButton235.Name = "Color"
ImageButton235.Parent = ImageButton233
ImageButton235.Position = UDim2.new(25.8659992, 0, -0.0829999968, 0)
ImageButton235.Size = UDim2.new(0, 40, 0, 14)
ImageButton235.BackgroundColor = BrickColor.new("Institutional white")
ImageButton235.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton235.BorderColor = BrickColor.new("Really black")
ImageButton235.BorderColor3 = Color3.new(0.0823529, 0.0823529, 0.0823529)
ImageButton235.BorderSizePixel = 2
ImageButton235.Image = "rbxassetid://5761429802"
ImageButton235.ImageTransparency = 0.60000002384186
ImageButton236.Name = "Teammates"
ImageButton236.Parent = Frame196
ImageButton236.Position = UDim2.new(0.0896226466, 0, 0.0492116101, 0)
ImageButton236.Size = UDim2.new(0, 12, 0, 12)
ImageButton236.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton236.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton236.BorderColor = BrickColor.new("Really black")
ImageButton236.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton236.Image = "rbxassetid://5761429802"
ImageButton236.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton236.ImageTransparency = 0.25
LocalScript237.Name = "teammates"
LocalScript237.Parent = ImageButton236
table.insert(cors,sandbox(LocalScript237,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
	end
end

button.Activated:Connect(onButtonActivated)
end))
TextLabel238.Name = "teammates"
TextLabel238.Parent = ImageButton236
TextLabel238.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel238.Size = UDim2.new(0, 324, 0, 20)
TextLabel238.BackgroundColor = BrickColor.new("Institutional white")
TextLabel238.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel238.BackgroundTransparency = 1
TextLabel238.Font = Enum.Font.SourceSans
TextLabel238.FontSize = Enum.FontSize.Size28
TextLabel238.Text = "Teammates"
TextLabel238.TextColor = BrickColor.new("Institutional white")
TextLabel238.TextColor3 = Color3.new(1, 1, 1)
TextLabel238.TextSize = 26
TextLabel238.TextWrap = true
TextLabel238.TextWrapped = true
TextLabel238.TextXAlignment = Enum.TextXAlignment.Left
ImageButton239.Name = "Icon"
ImageButton239.Parent = Frame83
ImageButton239.Position = UDim2.new(0.00613496918, 0, 0.097943373, 0)
ImageButton239.Size = UDim2.new(0, 160, 0, 114)
ImageButton239.BackgroundColor = BrickColor.new("Really black")
ImageButton239.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton239.BackgroundTransparency = 1
ImageButton239.BorderColor = BrickColor.new("Really black")
ImageButton239.BorderColor3 = Color3.new(0, 0, 0)
ImageButton239.ZIndex = 100
ImageButton239.Image = "rbxassetid://5750434205"
ImageButton239.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton239.ScaleType = Enum.ScaleType.Fit
Frame240.Name = "Side Border"
Frame240.Parent = Frame83
Frame240.Position = UDim2.new(1, 0, -0.0211267602, 0)
Frame240.Size = UDim2.new(0, 3, 0, 145)
Frame240.BackgroundColor = BrickColor.new("Dirt brown")
Frame240.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame240.BorderSizePixel = 0
Frame240.ZIndex = 2
Frame241.Name = "Other border"
Frame241.Parent = Frame83
Frame241.Position = UDim2.new(0, 0, 0, -3)
Frame241.Visible = false
Frame241.Size = UDim2.new(0, 166, 0, 3)
Frame241.BackgroundColor = BrickColor.new("Dirt brown")
Frame241.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame241.BorderSizePixel = 0
Frame241.ZIndex = 3
Frame242.Name = "User"
Frame242.Parent = Frame18
Frame242.Position = UDim2.new(0, 0, 0.858048618, 0)
Frame242.Size = UDim2.new(0, 163, 0, 144)
Frame242.BackgroundColor = BrickColor.new("Really black")
Frame242.BackgroundColor3 = Color3.new(0, 0, 0)
Frame242.BorderColor = BrickColor.new("Really black")
Frame242.BorderColor3 = Color3.new(0, 0, 0)
Frame242.BorderSizePixel = 0
LocalScript243.Name = "Selected"
LocalScript243.Parent = Frame242
table.insert(cors,sandbox(LocalScript243,function()
local button = script.Parent.Icon


local function onMouseEntered()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.Icon.ImageColor3 ~= Color3.new(1, 1, 1)then
				script.Parent.Icon.ImageColor3 = Color3.new(1, 1, 1)
			end
		end
		button.Activated:Connect(onButtonActivated)
	end
	
end
local function onMouseLeft()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end

     
	
button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
Frame244.Name = "Main"
Frame244.Parent = Frame242
Frame244.Position = UDim2.new(1.12899995, 0, -6, 0)
Frame244.Visible = false
Frame244.Size = UDim2.new(0, 941, 0, 993)
Frame244.BackgroundColor = BrickColor.new("Really blue")
Frame244.BackgroundColor3 = Color3.new(0, 0.0156863, 1)
Frame244.BackgroundTransparency = 1
Frame244.BorderSizePixel = 0
Frame245.Name = "PlayersTab"
Frame245.Parent = Frame244
Frame245.Position = UDim2.new(0.0236982461, 0, 0.0315125808, 0)
Frame245.Size = UDim2.new(0, 424, 0, 953)
Frame245.BackgroundColor = BrickColor.new("Really black")
Frame245.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame245.BorderColor = BrickColor.new("Dirt brown")
Frame245.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame245.BorderSizePixel = 2
TextLabel246.Name = "Players"
TextLabel246.Parent = Frame245
TextLabel246.Position = UDim2.new(0.0361394361, 0, -0.00979359634, 0)
TextLabel246.Size = UDim2.new(0, 114, 0, 10)
TextLabel246.Active = true
TextLabel246.BackgroundColor = BrickColor.new("Really black")
TextLabel246.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel246.BorderColor = BrickColor.new("Really black")
TextLabel246.BorderColor3 = Color3.new(0, 0, 0)
TextLabel246.BorderSizePixel = 0
TextLabel246.ZIndex = 2
TextLabel246.Font = Enum.Font.SourceSansBold
TextLabel246.FontSize = Enum.FontSize.Size28
TextLabel246.Text = "Player list"
TextLabel246.TextColor = BrickColor.new("Mid gray")
TextLabel246.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel246.TextSize = 28
TextLabel246.TextWrap = true
TextLabel246.TextWrapped = true
Frame247.Name = "PlayerList"
Frame247.Parent = Frame245
Frame247.Position = UDim2.new(0.0361394361, 0, 0.0162729453, 0)
Frame247.Size = UDim2.new(0.927750409, 0, 0.968538344, 0)
Frame247.BackgroundColor = BrickColor.new("Earth green")
Frame247.BackgroundColor3 = Color3.new(0.219608, 0.219608, 0.219608)
Frame247.BackgroundTransparency = 1
Frame247.BorderSizePixel = 0
TextButton248.Name = "14"
TextButton248.Parent = Frame247
TextButton248.Position = UDim2.new(0, 0, 0.637000024, 0)
TextButton248.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton248.BackgroundColor = BrickColor.new("Institutional white")
TextButton248.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton248.BackgroundTransparency = 1
TextButton248.BorderSizePixel = 0
TextButton248.Font = Enum.Font.SourceSans
TextButton248.FontSize = Enum.FontSize.Size28
TextButton248.Text = "[...]"
TextButton248.TextColor = BrickColor.new("Institutional white")
TextButton248.TextColor3 = Color3.new(1, 1, 1)
TextButton248.TextSize = 28
TextButton248.TextXAlignment = Enum.TextXAlignment.Left
LocalScript249.Name = "Stats"
LocalScript249.Parent = TextButton248
table.insert(cors,sandbox(LocalScript249,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
LocalScript250.Name = "A"
LocalScript250.Parent = Frame247
table.insert(cors,sandbox(LocalScript250,function()
function reset()
game:GetService("Players")
	local players=game.Players:GetChildren()
	for list = 1,14,1 do
		local num=tonumber(list)
		if players[num]~=nil then
			script.Parent:FindFirstChild(tonumber(list)).Text = players[num].Name
			script.Parent:FindFirstChild(tonumber(list)).TextColor3 = Color3.new(0,0,0)
			script.Parent:FindFirstChild(tonumber(list)).TextColor3 =  players[num].TeamColor.Color

		else	
			script.Parent:FindFirstChild(tonumber(list)).Text = "[...]"

		end
	end
end

while wait() do
	script.Parent["1"].Text = "[...]"
	script.Parent["2"].Text = "[...]"
	script.Parent["3"].Text = "[...]"
	script.Parent["4"].Text = "[...]"
	script.Parent["5"].Text = "[...]"
	script.Parent["6"].Text = "[...]"
	script.Parent["7"].Text = "[...]"
	script.Parent["8"].Text = "[...]"
	script.Parent["9"].Text = "[...]"
	script.Parent["10"].Text = "[...]"
	script.Parent["11"].Text = "[...]"
	script.Parent["12"].Text = "[...]"
	script.Parent["13"].Text = "[...]"
	script.Parent["14"].Text = "[...]"
	
	script.Parent["1"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["2"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["3"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["4"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["5"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["6"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["7"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["8"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["9"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["10"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["11"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["12"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["13"].TextColor3 = Color3.fromRGB(255, 255, 255)
	script.Parent["14"].TextColor3 = Color3.fromRGB(255, 255, 255)
	reset()
end
end))
TextButton251.Name = "5"
TextButton251.Parent = Frame247
TextButton251.Position = UDim2.new(0, 0, 0.195999995, 0)
TextButton251.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton251.BackgroundColor = BrickColor.new("Institutional white")
TextButton251.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton251.BackgroundTransparency = 1
TextButton251.BorderSizePixel = 0
TextButton251.Font = Enum.Font.SourceSans
TextButton251.FontSize = Enum.FontSize.Size28
TextButton251.Text = "[...]"
TextButton251.TextColor = BrickColor.new("Institutional white")
TextButton251.TextColor3 = Color3.new(1, 1, 1)
TextButton251.TextSize = 28
TextButton251.TextXAlignment = Enum.TextXAlignment.Left
LocalScript252.Name = "Stats"
LocalScript252.Parent = TextButton251
table.insert(cors,sandbox(LocalScript252,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton253.Name = "4"
TextButton253.Parent = Frame247
TextButton253.Position = UDim2.new(0, 0, 0.147, 0)
TextButton253.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton253.BackgroundColor = BrickColor.new("Institutional white")
TextButton253.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton253.BackgroundTransparency = 1
TextButton253.BorderSizePixel = 0
TextButton253.Font = Enum.Font.SourceSans
TextButton253.FontSize = Enum.FontSize.Size28
TextButton253.Text = "[...]"
TextButton253.TextColor = BrickColor.new("Institutional white")
TextButton253.TextColor3 = Color3.new(1, 1, 1)
TextButton253.TextSize = 28
TextButton253.TextXAlignment = Enum.TextXAlignment.Left
LocalScript254.Name = "Stats"
LocalScript254.Parent = TextButton253
table.insert(cors,sandbox(LocalScript254,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton255.Name = "3"
TextButton255.Parent = Frame247
TextButton255.Position = UDim2.new(0, 0, 0.097506322, 0)
TextButton255.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton255.BackgroundColor = BrickColor.new("Institutional white")
TextButton255.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton255.BackgroundTransparency = 1
TextButton255.BorderSizePixel = 0
TextButton255.Font = Enum.Font.SourceSans
TextButton255.FontSize = Enum.FontSize.Size28
TextButton255.Text = "[...]"
TextButton255.TextColor = BrickColor.new("Institutional white")
TextButton255.TextColor3 = Color3.new(1, 1, 1)
TextButton255.TextSize = 28
TextButton255.TextXAlignment = Enum.TextXAlignment.Left
LocalScript256.Name = "Stats"
LocalScript256.Parent = TextButton255
table.insert(cors,sandbox(LocalScript256,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton257.Name = "2"
TextButton257.Parent = Frame247
TextButton257.Position = UDim2.new(0, 0, 0.0489999987, 0)
TextButton257.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton257.BackgroundColor = BrickColor.new("Institutional white")
TextButton257.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton257.BackgroundTransparency = 1
TextButton257.BorderSizePixel = 0
TextButton257.Font = Enum.Font.SourceSans
TextButton257.FontSize = Enum.FontSize.Size28
TextButton257.Text = "[...]"
TextButton257.TextColor = BrickColor.new("Institutional white")
TextButton257.TextColor3 = Color3.new(1, 1, 1)
TextButton257.TextSize = 28
TextButton257.TextXAlignment = Enum.TextXAlignment.Left
LocalScript258.Name = "Stats"
LocalScript258.Parent = TextButton257
table.insert(cors,sandbox(LocalScript258,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton259.Name = "1"
TextButton259.Parent = Frame247
TextButton259.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton259.BackgroundColor = BrickColor.new("Neon green")
TextButton259.BackgroundColor3 = Color3.new(0.760784, 1, 0.317647)
TextButton259.BackgroundTransparency = 1
TextButton259.BorderSizePixel = 0
TextButton259.Font = Enum.Font.SourceSans
TextButton259.FontSize = Enum.FontSize.Size28
TextButton259.Text = "[...]"
TextButton259.TextColor = BrickColor.new("White")
TextButton259.TextColor3 = Color3.new(0.94902, 0.952941, 0.952941)
TextButton259.TextSize = 28
TextButton259.TextXAlignment = Enum.TextXAlignment.Left
LocalScript260.Name = "Stats"
LocalScript260.Parent = TextButton259
table.insert(cors,sandbox(LocalScript260,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton261.Name = "8"
TextButton261.Parent = Frame247
TextButton261.Position = UDim2.new(0, 0, 0.342999995, 0)
TextButton261.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton261.BackgroundColor = BrickColor.new("Institutional white")
TextButton261.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton261.BackgroundTransparency = 1
TextButton261.BorderSizePixel = 0
TextButton261.Font = Enum.Font.SourceSans
TextButton261.FontSize = Enum.FontSize.Size28
TextButton261.Text = "[...]"
TextButton261.TextColor = BrickColor.new("Institutional white")
TextButton261.TextColor3 = Color3.new(1, 1, 1)
TextButton261.TextSize = 28
TextButton261.TextXAlignment = Enum.TextXAlignment.Left
LocalScript262.Name = "Stats"
LocalScript262.Parent = TextButton261
table.insert(cors,sandbox(LocalScript262,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton263.Name = "9"
TextButton263.Parent = Frame247
TextButton263.Position = UDim2.new(0, 0, 0.39199999, 0)
TextButton263.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton263.BackgroundColor = BrickColor.new("Institutional white")
TextButton263.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton263.BackgroundTransparency = 1
TextButton263.BorderSizePixel = 0
TextButton263.Font = Enum.Font.SourceSans
TextButton263.FontSize = Enum.FontSize.Size28
TextButton263.Text = "[...]"
TextButton263.TextColor = BrickColor.new("Institutional white")
TextButton263.TextColor3 = Color3.new(1, 1, 1)
TextButton263.TextSize = 28
TextButton263.TextXAlignment = Enum.TextXAlignment.Left
LocalScript264.Name = "Stats"
LocalScript264.Parent = TextButton263
table.insert(cors,sandbox(LocalScript264,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton265.Name = "10"
TextButton265.Parent = Frame247
TextButton265.Position = UDim2.new(0, 0, 0.441000015, 0)
TextButton265.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton265.BackgroundColor = BrickColor.new("Institutional white")
TextButton265.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton265.BackgroundTransparency = 1
TextButton265.BorderSizePixel = 0
TextButton265.Font = Enum.Font.SourceSans
TextButton265.FontSize = Enum.FontSize.Size28
TextButton265.Text = "[...]"
TextButton265.TextColor = BrickColor.new("Institutional white")
TextButton265.TextColor3 = Color3.new(1, 1, 1)
TextButton265.TextSize = 28
TextButton265.TextXAlignment = Enum.TextXAlignment.Left
LocalScript266.Name = "Stats"
LocalScript266.Parent = TextButton265
table.insert(cors,sandbox(LocalScript266,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton267.Name = "11"
TextButton267.Parent = Frame247
TextButton267.Position = UDim2.new(0, 0, 0.49000001, 0)
TextButton267.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton267.BackgroundColor = BrickColor.new("Institutional white")
TextButton267.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton267.BackgroundTransparency = 1
TextButton267.BorderSizePixel = 0
TextButton267.Font = Enum.Font.SourceSans
TextButton267.FontSize = Enum.FontSize.Size28
TextButton267.Text = "[...]"
TextButton267.TextColor = BrickColor.new("Institutional white")
TextButton267.TextColor3 = Color3.new(1, 1, 1)
TextButton267.TextSize = 28
TextButton267.TextXAlignment = Enum.TextXAlignment.Left
LocalScript268.Name = "Stats"
LocalScript268.Parent = TextButton267
table.insert(cors,sandbox(LocalScript268,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton269.Name = "12"
TextButton269.Parent = Frame247
TextButton269.Position = UDim2.new(0, 0, 0.538999975, 0)
TextButton269.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton269.BackgroundColor = BrickColor.new("Institutional white")
TextButton269.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton269.BackgroundTransparency = 1
TextButton269.BorderSizePixel = 0
TextButton269.Font = Enum.Font.SourceSans
TextButton269.FontSize = Enum.FontSize.Size28
TextButton269.Text = "[...]"
TextButton269.TextColor = BrickColor.new("Institutional white")
TextButton269.TextColor3 = Color3.new(1, 1, 1)
TextButton269.TextSize = 28
TextButton269.TextXAlignment = Enum.TextXAlignment.Left
LocalScript270.Name = "Stats"
LocalScript270.Parent = TextButton269
table.insert(cors,sandbox(LocalScript270,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton271.Name = "6"
TextButton271.Parent = Frame247
TextButton271.Position = UDim2.new(0, 0, 0.245000005, 0)
TextButton271.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton271.BackgroundColor = BrickColor.new("Institutional white")
TextButton271.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton271.BackgroundTransparency = 1
TextButton271.BorderSizePixel = 0
TextButton271.Font = Enum.Font.SourceSans
TextButton271.FontSize = Enum.FontSize.Size28
TextButton271.Text = "[...]"
TextButton271.TextColor = BrickColor.new("Institutional white")
TextButton271.TextColor3 = Color3.new(1, 1, 1)
TextButton271.TextSize = 28
TextButton271.TextXAlignment = Enum.TextXAlignment.Left
LocalScript272.Name = "Stats"
LocalScript272.Parent = TextButton271
table.insert(cors,sandbox(LocalScript272,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton273.Name = "7"
TextButton273.Parent = Frame247
TextButton273.Position = UDim2.new(0, 0, 0.294, 0)
TextButton273.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton273.BackgroundColor = BrickColor.new("Institutional white")
TextButton273.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton273.BackgroundTransparency = 1
TextButton273.BorderSizePixel = 0
TextButton273.Font = Enum.Font.SourceSans
TextButton273.FontSize = Enum.FontSize.Size28
TextButton273.Text = "[...]"
TextButton273.TextColor = BrickColor.new("Institutional white")
TextButton273.TextColor3 = Color3.new(1, 1, 1)
TextButton273.TextSize = 28
TextButton273.TextXAlignment = Enum.TextXAlignment.Left
LocalScript274.Name = "Stats"
LocalScript274.Parent = TextButton273
table.insert(cors,sandbox(LocalScript274,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
TextButton275.Name = "13"
TextButton275.Parent = Frame247
TextButton275.Position = UDim2.new(0, 0, 0.588, 0)
TextButton275.Size = UDim2.new(1, 0, 0.0487270728, 0)
TextButton275.BackgroundColor = BrickColor.new("Institutional white")
TextButton275.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton275.BackgroundTransparency = 1
TextButton275.BorderSizePixel = 0
TextButton275.Font = Enum.Font.SourceSans
TextButton275.FontSize = Enum.FontSize.Size28
TextButton275.Text = "[...]"
TextButton275.TextColor = BrickColor.new("Institutional white")
TextButton275.TextColor3 = Color3.new(1, 1, 1)
TextButton275.TextSize = 28
TextButton275.TextXAlignment = Enum.TextXAlignment.Left
LocalScript276.Name = "Stats"
LocalScript276.Parent = TextButton275
table.insert(cors,sandbox(LocalScript276,function()
while wait() do
	--	local s = script 
	--	for _, v in pairs( script.Parent:GetDescendants() ) do 
	--		if v:IsA("TextButton") and v.Name ~= "Template" then s:Clone().Parent = v
	--		end 
	--	end
	--	if script.Parent:IsA("TextButton") and script.Parent.Name ~= "Template"then
			game:GetService("Players")
			local plrnam = script.Parent.Text
			local Player = game.Players:FindFirstChild(plrnam)
			local button = script.Parent

			local function onButtonActivated()
				script.Parent.Parent.Parent.Parent.OtherTab.Age2.Text = Player.AccountAge
				script.Parent.Parent.Parent.Parent.OtherTab.UID2.Text = Player.UserId
				--local ass = gethiddenproperty or get_hidden_prop
				--local Thing = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
				--local ParsedCountry = Thing[ass(Player, "CountryRegionCodeReplicate")]
				--script.Parent.Parent.Parent.Parent.OtherTab.extra2.Text = tostring(ParsedCountry)
				if Player.MembershipType == Enum.MembershipType.Premium then
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("Yes")
				else
					script.Parent.Parent.Parent.Parent.OtherTab.Club2.Text = ("No")


					script.Parent.Parent.Parent.Parent.OtherTab.Pic2.Image = "https://www.roblox.com/bust-thumbnail/image?userId=" ..Player.UserId.."&width=420&height=420&format=png"

				end

			end
			button.Activated:Connect(onButtonActivated)
	--	end
end

end))
Frame277.Name = "OtherTab"
Frame277.Parent = Frame244
Frame277.Position = UDim2.new(0.526000082, 0, 0.0320000015, 0)
Frame277.Size = UDim2.new(0, 424, 0, 953)
Frame277.BackgroundColor = BrickColor.new("Really black")
Frame277.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame277.BorderColor = BrickColor.new("Dirt brown")
Frame277.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame277.BorderSizePixel = 2
TextLabel278.Name = "Info"
TextLabel278.Parent = Frame277
TextLabel278.Position = UDim2.new(0.0359999985, 0, -0.00899999961, 0)
TextLabel278.Size = UDim2.new(0, 51, 0, 10)
TextLabel278.Active = true
TextLabel278.BackgroundColor = BrickColor.new("Really black")
TextLabel278.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel278.BorderColor = BrickColor.new("Really black")
TextLabel278.BorderColor3 = Color3.new(0, 0, 0)
TextLabel278.BorderSizePixel = 0
TextLabel278.ZIndex = 2
TextLabel278.Font = Enum.Font.SourceSansBold
TextLabel278.FontSize = Enum.FontSize.Size28
TextLabel278.Text = "Info"
TextLabel278.TextColor = BrickColor.new("Mid gray")
TextLabel278.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel278.TextSize = 28
TextLabel278.TextWrap = true
TextLabel278.TextWrapped = true
TextLabel279.Name = "extra"
TextLabel279.Parent = Frame277
TextLabel279.Position = UDim2.new(0, 22, 0, 68)
TextLabel279.Size = UDim2.new(0, 400, 0, 30)
TextLabel279.BackgroundColor = BrickColor.new("Institutional white")
TextLabel279.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel279.BackgroundTransparency = 1
TextLabel279.BorderSizePixel = 0
TextLabel279.Font = Enum.Font.SourceSans
TextLabel279.FontSize = Enum.FontSize.Size28
TextLabel279.Text = "Country:"
TextLabel279.TextColor = BrickColor.new("Institutional white")
TextLabel279.TextColor3 = Color3.new(1, 1, 1)
TextLabel279.TextSize = 28
TextLabel279.TextXAlignment = Enum.TextXAlignment.Left
TextLabel280.Name = "UID"
TextLabel280.Parent = Frame277
TextLabel280.Position = UDim2.new(0, 22, 0, 106)
TextLabel280.Size = UDim2.new(0, 400, 0, 30)
TextLabel280.BackgroundColor = BrickColor.new("Institutional white")
TextLabel280.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel280.BackgroundTransparency = 1
TextLabel280.BorderSizePixel = 0
TextLabel280.Font = Enum.Font.SourceSans
TextLabel280.FontSize = Enum.FontSize.Size28
TextLabel280.Text = "UID:"
TextLabel280.TextColor = BrickColor.new("Institutional white")
TextLabel280.TextColor3 = Color3.new(1, 1, 1)
TextLabel280.TextSize = 28
TextLabel280.TextXAlignment = Enum.TextXAlignment.Left
TextLabel281.Name = "Age2"
TextLabel281.Parent = Frame277
TextLabel281.Position = UDim2.new(0, 22, 0, 30)
TextLabel281.Size = UDim2.new(0, 400, 0, 30)
TextLabel281.BackgroundColor = BrickColor.new("Institutional white")
TextLabel281.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel281.BackgroundTransparency = 1
TextLabel281.BorderSizePixel = 0
TextLabel281.Font = Enum.Font.SourceSans
TextLabel281.FontSize = Enum.FontSize.Size28
TextLabel281.Text = ""
TextLabel281.TextColor = BrickColor.new("Institutional white")
TextLabel281.TextColor3 = Color3.new(1, 1, 1)
TextLabel281.TextSize = 28
TextLabel281.TextXAlignment = Enum.TextXAlignment.Right
TextLabel282.Name = "Pic"
TextLabel282.Parent = Frame277
TextLabel282.Position = UDim2.new(0, 22, 0, 182)
TextLabel282.Size = UDim2.new(0, 400, 0, 30)
TextLabel282.BackgroundColor = BrickColor.new("Institutional white")
TextLabel282.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel282.BackgroundTransparency = 1
TextLabel282.BorderSizePixel = 0
TextLabel282.Font = Enum.Font.SourceSans
TextLabel282.FontSize = Enum.FontSize.Size28
TextLabel282.Text = "Picture:"
TextLabel282.TextColor = BrickColor.new("Institutional white")
TextLabel282.TextColor3 = Color3.new(1, 1, 1)
TextLabel282.TextSize = 28
TextLabel282.TextXAlignment = Enum.TextXAlignment.Left
TextLabel283.Name = "UID2"
TextLabel283.Parent = Frame277
TextLabel283.Position = UDim2.new(0, 22, 0, 106)
TextLabel283.Size = UDim2.new(0, 400, 0, 30)
TextLabel283.BackgroundColor = BrickColor.new("Institutional white")
TextLabel283.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel283.BackgroundTransparency = 1
TextLabel283.BorderSizePixel = 0
TextLabel283.Font = Enum.Font.SourceSans
TextLabel283.FontSize = Enum.FontSize.Size28
TextLabel283.Text = ""
TextLabel283.TextColor = BrickColor.new("Institutional white")
TextLabel283.TextColor3 = Color3.new(1, 1, 1)
TextLabel283.TextSize = 28
TextLabel283.TextXAlignment = Enum.TextXAlignment.Right
TextLabel284.Name = "Age"
TextLabel284.Parent = Frame277
TextLabel284.Position = UDim2.new(0, 22, 0, 30)
TextLabel284.Size = UDim2.new(0, 400, 0, 30)
TextLabel284.BackgroundColor = BrickColor.new("Institutional white")
TextLabel284.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel284.BackgroundTransparency = 1
TextLabel284.BorderSizePixel = 0
TextLabel284.Font = Enum.Font.SourceSans
TextLabel284.FontSize = Enum.FontSize.Size28
TextLabel284.Text = "Account age (days):"
TextLabel284.TextColor = BrickColor.new("Institutional white")
TextLabel284.TextColor3 = Color3.new(1, 1, 1)
TextLabel284.TextSize = 28
TextLabel284.TextXAlignment = Enum.TextXAlignment.Left
TextLabel285.Name = "Club2"
TextLabel285.Parent = Frame277
TextLabel285.Position = UDim2.new(0, 22, 0, 144)
TextLabel285.Size = UDim2.new(0, 400, 0, 30)
TextLabel285.BackgroundColor = BrickColor.new("Institutional white")
TextLabel285.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel285.BackgroundTransparency = 1
TextLabel285.BorderSizePixel = 0
TextLabel285.Font = Enum.Font.SourceSans
TextLabel285.FontSize = Enum.FontSize.Size28
TextLabel285.Text = ""
TextLabel285.TextColor = BrickColor.new("Institutional white")
TextLabel285.TextColor3 = Color3.new(1, 1, 1)
TextLabel285.TextSize = 28
TextLabel285.TextXAlignment = Enum.TextXAlignment.Right
TextLabel286.Name = "extra2"
TextLabel286.Parent = Frame277
TextLabel286.Position = UDim2.new(0, 22, 0, 68)
TextLabel286.Size = UDim2.new(0, 400, 0, 30)
TextLabel286.BackgroundColor = BrickColor.new("Institutional white")
TextLabel286.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel286.BackgroundTransparency = 1
TextLabel286.BorderSizePixel = 0
TextLabel286.Font = Enum.Font.SourceSans
TextLabel286.FontSize = Enum.FontSize.Size28
TextLabel286.Text = ""
TextLabel286.TextColor = BrickColor.new("Institutional white")
TextLabel286.TextColor3 = Color3.new(1, 1, 1)
TextLabel286.TextSize = 28
TextLabel286.TextXAlignment = Enum.TextXAlignment.Right
TextLabel287.Name = "Club"
TextLabel287.Parent = Frame277
TextLabel287.Position = UDim2.new(0, 22, 0, 144)
TextLabel287.Size = UDim2.new(0, 400, 0, 30)
TextLabel287.BackgroundColor = BrickColor.new("Institutional white")
TextLabel287.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel287.BackgroundTransparency = 1
TextLabel287.BorderSizePixel = 0
TextLabel287.Font = Enum.Font.SourceSans
TextLabel287.FontSize = Enum.FontSize.Size28
TextLabel287.Text = "Premium:"
TextLabel287.TextColor = BrickColor.new("Institutional white")
TextLabel287.TextColor3 = Color3.new(1, 1, 1)
TextLabel287.TextSize = 28
TextLabel287.TextXAlignment = Enum.TextXAlignment.Left
ImageButton288.Name = "Pic2"
ImageButton288.Parent = Frame277
ImageButton288.Position = UDim2.new(0.0680000037, 0, 0.240999997, 0)
ImageButton288.Size = UDim2.new(0, 365, 0, 365)
ImageButton288.BackgroundColor = BrickColor.new("Really black")
ImageButton288.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton288.BorderColor = BrickColor.new("Dirt brown")
ImageButton288.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
ImageButton288.BorderSizePixel = 3
ImageButton288.ScaleType = Enum.ScaleType.Fit
ImageButton289.Name = "Icon"
ImageButton289.Parent = Frame242
ImageButton289.Position = UDim2.new(0, 1, 0, 0)
ImageButton289.Size = UDim2.new(0, 160, 0, 135)
ImageButton289.BackgroundColor = BrickColor.new("Really black")
ImageButton289.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton289.BackgroundTransparency = 1
ImageButton289.BorderColor = BrickColor.new("Really black")
ImageButton289.BorderColor3 = Color3.new(0, 0, 0)
ImageButton289.ZIndex = 100
ImageButton289.Image = "rbxassetid://5750439594"
ImageButton289.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton289.ScaleType = Enum.ScaleType.Fit
Frame290.Name = "Side Border"
Frame290.Parent = Frame242
Frame290.Position = UDim2.new(1, 0, 0.0069444445, -4)
Frame290.Size = UDim2.new(0, 3, 0, 154)
Frame290.BackgroundColor = BrickColor.new("Dirt brown")
Frame290.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame290.BorderSizePixel = 0
Frame290.ZIndex = 2
Frame291.Name = "Other border"
Frame291.Parent = Frame242
Frame291.Position = UDim2.new(0, 0, 0, -3)
Frame291.Visible = false
Frame291.Size = UDim2.new(0, 166, 0, 3)
Frame291.BackgroundColor = BrickColor.new("Dirt brown")
Frame291.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame291.BorderSizePixel = 0
Frame291.ZIndex = 3
Frame292.Name = "Skins"
Frame292.Parent = Frame18
Frame292.Position = UDim2.new(0, 0, 0.708065569, 0)
Frame292.Size = UDim2.new(0, 163, 0, 149)
Frame292.BackgroundColor = BrickColor.new("Really black")
Frame292.BackgroundColor3 = Color3.new(0, 0, 0)
Frame292.BorderColor = BrickColor.new("Really black")
Frame292.BorderColor3 = Color3.new(0, 0, 0)
Frame292.BorderSizePixel = 0
LocalScript293.Name = "Selected"
LocalScript293.Parent = Frame292
table.insert(cors,sandbox(LocalScript293,function()
local button = script.Parent.Icon


local function onMouseEntered()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.Icon.ImageColor3 ~= Color3.new(1, 1, 1)then
				script.Parent.Icon.ImageColor3 = Color3.new(1, 1, 1)
			end
		end
		button.Activated:Connect(onButtonActivated)
	end
	
end
local function onMouseLeft()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end

     
	
button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton294.Name = "Icon"
ImageButton294.Parent = Frame292
ImageButton294.Position = UDim2.new(0.0104141701, 0, 0.0468139648, 0)
ImageButton294.Size = UDim2.new(0, 161, 0, 135)
ImageButton294.BackgroundColor = BrickColor.new("Really black")
ImageButton294.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton294.BackgroundTransparency = 1
ImageButton294.BorderColor = BrickColor.new("Really black")
ImageButton294.BorderColor3 = Color3.new(0, 0, 0)
ImageButton294.ZIndex = 100
ImageButton294.Image = "rbxassetid://5752461306"
ImageButton294.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton294.ScaleType = Enum.ScaleType.Fit
Frame295.Name = "Side Border"
Frame295.Parent = Frame292
Frame295.Position = UDim2.new(1, 0, 0, 0)
Frame295.Size = UDim2.new(0, 3, 0, 152)
Frame295.BackgroundColor = BrickColor.new("Dirt brown")
Frame295.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame295.BorderSizePixel = 0
Frame295.ZIndex = 2
Frame296.Name = "Other border"
Frame296.Parent = Frame292
Frame296.Visible = false
Frame296.Size = UDim2.new(0, 166, 0, 3)
Frame296.BackgroundColor = BrickColor.new("Dirt brown")
Frame296.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame296.BorderSizePixel = 0
Frame296.ZIndex = 5
Frame297.Name = "Main"
Frame297.Parent = Frame292
Frame297.Position = UDim2.new(1.12300003, 0, -4.76999998, 0)
Frame297.Visible = false
Frame297.Size = UDim2.new(0, 941, 0, 993)
Frame297.BackgroundColor = BrickColor.new("Deep orange")
Frame297.BackgroundColor3 = Color3.new(1, 0.533333, 0)
Frame297.BackgroundTransparency = 1
Frame297.BorderSizePixel = 0
Frame298.Name = "SkinTab"
Frame298.Parent = Frame297
Frame298.Position = UDim2.new(0.526000082, 0, 0.0329999812, 0)
Frame298.Size = UDim2.new(0, 424, 0, 952)
Frame298.BackgroundColor = BrickColor.new("Really black")
Frame298.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame298.BorderColor = BrickColor.new("Dirt brown")
Frame298.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame298.BorderSizePixel = 2
TextLabel299.Name = "Weapon skin"
TextLabel299.Parent = Frame298
TextLabel299.Position = UDim2.new(0.0361394361, 0, -0.00979359634, 0)
TextLabel299.Size = UDim2.new(0, 138, 0, 10)
TextLabel299.Active = true
TextLabel299.BackgroundColor = BrickColor.new("Really black")
TextLabel299.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel299.BorderColor = BrickColor.new("Really black")
TextLabel299.BorderColor3 = Color3.new(0, 0, 0)
TextLabel299.BorderSizePixel = 0
TextLabel299.ZIndex = 2
TextLabel299.Font = Enum.Font.SourceSansBold
TextLabel299.FontSize = Enum.FontSize.Size28
TextLabel299.Text = "Weapon skin"
TextLabel299.TextColor = BrickColor.new("Mid gray")
TextLabel299.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel299.TextSize = 28
TextLabel299.TextWrap = true
TextLabel299.TextWrapped = true
Frame300.Name = "KnifeTab"
Frame300.Parent = Frame297
Frame300.Position = UDim2.new(0.0233433247, 0, 0.0330070518, 0)
Frame300.Size = UDim2.new(0, 424, 0, 283)
Frame300.BackgroundColor = BrickColor.new("Really black")
Frame300.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame300.BorderColor = BrickColor.new("Dirt brown")
Frame300.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame300.BorderSizePixel = 2
TextLabel301.Name = "Knife Options"
TextLabel301.Parent = Frame300
TextLabel301.Position = UDim2.new(0.0361394361, 0, -0.0346901305, 0)
TextLabel301.Size = UDim2.new(0, 147, 0, 10)
TextLabel301.Active = true
TextLabel301.BackgroundColor = BrickColor.new("Really black")
TextLabel301.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel301.BorderColor = BrickColor.new("Really black")
TextLabel301.BorderColor3 = Color3.new(0, 0, 0)
TextLabel301.BorderSizePixel = 0
TextLabel301.ZIndex = 2
TextLabel301.Font = Enum.Font.SourceSansBold
TextLabel301.FontSize = Enum.FontSize.Size28
TextLabel301.Text = "Knife Options"
TextLabel301.TextColor = BrickColor.new("Mid gray")
TextLabel301.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel301.TextSize = 28
TextLabel301.TextWrap = true
TextLabel301.TextWrapped = true
Frame302.Name = "GloveTab"
Frame302.Parent = Frame297
Frame302.Position = UDim2.new(0.0233433209, 0, 0.364971787, 0)
Frame302.Size = UDim2.new(0, 424, 0, 623)
Frame302.BackgroundColor = BrickColor.new("Really black")
Frame302.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame302.BorderColor = BrickColor.new("Dirt brown")
Frame302.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame302.BorderSizePixel = 2
TextLabel303.Name = "Golve options"
TextLabel303.Parent = Frame302
TextLabel303.Position = UDim2.new(0.0359999463, 0, -0.0159999859, 1)
TextLabel303.Size = UDim2.new(0, 147, 0, 9)
TextLabel303.Active = true
TextLabel303.BackgroundColor = BrickColor.new("Really black")
TextLabel303.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel303.BorderColor = BrickColor.new("Really black")
TextLabel303.BorderColor3 = Color3.new(0, 0, 0)
TextLabel303.BorderSizePixel = 0
TextLabel303.ZIndex = 2
TextLabel303.Font = Enum.Font.SourceSansBold
TextLabel303.FontSize = Enum.FontSize.Size28
TextLabel303.Text = "Golve options"
TextLabel303.TextColor = BrickColor.new("Mid gray")
TextLabel303.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel303.TextSize = 28
TextLabel303.TextWrap = true
TextLabel303.TextWrapped = true
Frame304.Name = "Settings"
Frame304.Parent = Frame18
Frame304.Position = UDim2.new(0, 0, 0.567188621, 0)
Frame304.Size = UDim2.new(0, 163, 0, 142)
Frame304.BackgroundColor = BrickColor.new("Really black")
Frame304.BackgroundColor3 = Color3.new(0, 0, 0)
Frame304.BorderColor = BrickColor.new("Really black")
Frame304.BorderColor3 = Color3.new(0, 0, 0)
Frame304.BorderSizePixel = 0
LocalScript305.Name = "Selected"
LocalScript305.Parent = Frame304
table.insert(cors,sandbox(LocalScript305,function()
local button = script.Parent.Icon


local function onMouseEntered()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.Icon.ImageColor3 ~= Color3.new(1, 1, 1)then
				script.Parent.Icon.ImageColor3 = Color3.new(1, 1, 1)
			end
		end
		button.Activated:Connect(onButtonActivated)
	end
	
end
local function onMouseLeft()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end

     
	
button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
Frame306.Name = "Main"
Frame306.Parent = Frame304
Frame306.Position = UDim2.new(1.12883437, 0, -3.98021245, 0)
Frame306.Visible = false
Frame306.Size = UDim2.new(0, 941, 0, 993)
Frame306.BackgroundColor = BrickColor.new("Hot pink")
Frame306.BackgroundColor3 = Color3.new(1, 0, 1)
Frame306.BackgroundTransparency = 1
Frame306.BorderSizePixel = 0
Frame307.Name = "OtherTab"
Frame307.Parent = Frame306
Frame307.Position = UDim2.new(0.526000082, 0, 0.363964736, 0)
Frame307.Size = UDim2.new(0, 424, 0, 624)
Frame307.BackgroundColor = BrickColor.new("Really black")
Frame307.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame307.BorderColor = BrickColor.new("Dirt brown")
Frame307.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame307.BorderSizePixel = 2
TextLabel308.Name = "Other"
TextLabel308.Parent = Frame307
TextLabel308.Position = UDim2.new(0.0359999985, 0, -0.0140000004, 1)
TextLabel308.Size = UDim2.new(0, 68, 0, 9)
TextLabel308.Active = true
TextLabel308.BackgroundColor = BrickColor.new("Really black")
TextLabel308.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel308.BorderColor = BrickColor.new("Really black")
TextLabel308.BorderColor3 = Color3.new(0, 0, 0)
TextLabel308.BorderSizePixel = 0
TextLabel308.ZIndex = 2
TextLabel308.Font = Enum.Font.SourceSansBold
TextLabel308.FontSize = Enum.FontSize.Size28
TextLabel308.Text = "Other"
TextLabel308.TextColor = BrickColor.new("Mid gray")
TextLabel308.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel308.TextSize = 28
TextLabel308.TextWrap = true
TextLabel308.TextWrapped = true
Frame309.Name = "SettingsTab"
Frame309.Parent = Frame306
Frame309.Position = UDim2.new(0.526000082, 0, 0.0320000015, 0)
Frame309.Size = UDim2.new(0, 424, 0, 283)
Frame309.BackgroundColor = BrickColor.new("Really black")
Frame309.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame309.BorderColor = BrickColor.new("Dirt brown")
Frame309.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame309.BorderSizePixel = 2
Frame310.Name = "DropDown"
Frame310.Parent = Frame309
Frame310.Position = UDim2.new(0.194999993, 0, 0.497999996, -3)
Frame310.Size = UDim2.new(0.61330384, 0, 0.0426017083, 0)
Frame310.BackgroundColor = BrickColor.new("Really black")
Frame310.BackgroundColor3 = Color3.new(0, 0, 0)
Frame310.BackgroundTransparency = 1
Frame310.BorderSizePixel = 0
Frame310.ZIndex = 3
TextButton311.Name = "Selection"
TextButton311.Parent = Frame310
TextButton311.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton311.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton311.BackgroundColor = BrickColor.new("Black")
TextButton311.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton311.BorderColor = BrickColor.new("Dirt brown")
TextButton311.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton311.BorderSizePixel = 3
TextButton311.Font = Enum.Font.SourceSans
TextButton311.FontSize = Enum.FontSize.Size28
TextButton311.Text = "[...]"
TextButton311.TextColor = BrickColor.new("Institutional white")
TextButton311.TextColor3 = Color3.new(1, 1, 1)
TextButton311.TextSize = 26
TextButton311.TextWrap = true
TextButton311.TextWrapped = true
Frame312.Name = "Menu"
Frame312.Parent = Frame310
Frame312.Position = UDim2.new(0, 0, -5.02100086, 3)
Frame312.Visible = false
Frame312.Size = UDim2.new(1, 0, 17.8091831, 0)
Frame312.BackgroundColor = BrickColor.new("Black")
Frame312.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame312.BorderColor = BrickColor.new("Dirt brown")
Frame312.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame312.BorderSizePixel = 3
Frame312.ZIndex = 4
TextButton313.Name = "Button5"
TextButton313.Parent = Frame312
TextButton313.Position = UDim2.new(0, 0, 0.665165007, 0)
TextButton313.Size = UDim2.new(1, 0, 0.00513475854, 35)
TextButton313.BackgroundColor = BrickColor.new("Black metallic")
TextButton313.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton313.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton313.BorderSizePixel = 0
TextButton313.ZIndex = 4
TextButton313.Font = Enum.Font.SourceSans
TextButton313.FontSize = Enum.FontSize.Size28
TextButton313.Text = "125%"
TextButton313.TextColor = BrickColor.new("Institutional white")
TextButton313.TextColor3 = Color3.new(1, 1, 1)
TextButton313.TextSize = 26
TextButton313.TextWrap = true
TextButton313.TextWrapped = true
TextButton314.Name = "Button4"
TextButton314.Parent = Frame312
TextButton314.Position = UDim2.new(0, 0, 0.497021973, 0)
TextButton314.Size = UDim2.new(1, 0, 0.00513475854, 35)
TextButton314.BackgroundColor = BrickColor.new("Black metallic")
TextButton314.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton314.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton314.BorderSizePixel = 0
TextButton314.ZIndex = 4
TextButton314.Font = Enum.Font.SourceSans
TextButton314.FontSize = Enum.FontSize.Size28
TextButton314.Text = "100%"
TextButton314.TextColor = BrickColor.new("Institutional white")
TextButton314.TextColor3 = Color3.new(1, 1, 1)
TextButton314.TextSize = 26
TextButton314.TextWrap = true
TextButton314.TextWrapped = true
TextButton315.Name = "Button"
TextButton315.Parent = Frame312
TextButton315.Position = UDim2.new(0, 0, 0.0046573896, 0)
TextButton315.Size = UDim2.new(1, 0, 0.00513475854, 35)
TextButton315.BackgroundColor = BrickColor.new("Black metallic")
TextButton315.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton315.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton315.BorderSizePixel = 0
TextButton315.ZIndex = 4
TextButton315.Font = Enum.Font.SourceSans
TextButton315.FontSize = Enum.FontSize.Size28
TextButton315.Text = "25%"
TextButton315.TextColor = BrickColor.new("Institutional white")
TextButton315.TextColor3 = Color3.new(1, 1, 1)
TextButton315.TextSize = 26
TextButton315.TextWrap = true
TextButton315.TextWrapped = true
TextButton316.Name = "Button2"
TextButton316.Parent = Frame312
TextButton316.Position = UDim2.new(0, 0, 0.161560729, 0)
TextButton316.Size = UDim2.new(1, 0, 0.00513475854, 35)
TextButton316.BackgroundColor = BrickColor.new("Black metallic")
TextButton316.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton316.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton316.BorderSizePixel = 0
TextButton316.ZIndex = 4
TextButton316.Font = Enum.Font.SourceSans
TextButton316.FontSize = Enum.FontSize.Size28
TextButton316.Text = "50%"
TextButton316.TextColor = BrickColor.new("Institutional white")
TextButton316.TextColor3 = Color3.new(1, 1, 1)
TextButton316.TextSize = 26
TextButton316.TextWrap = true
TextButton316.TextWrapped = true
TextButton317.Name = "Button3"
TextButton317.Parent = Frame312
TextButton317.Position = UDim2.new(0, 0, 0.329136074, 0)
TextButton317.Size = UDim2.new(1, 0, 0.00513475854, 35)
TextButton317.BackgroundColor = BrickColor.new("Black metallic")
TextButton317.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton317.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton317.BorderSizePixel = 0
TextButton317.ZIndex = 4
TextButton317.Font = Enum.Font.SourceSans
TextButton317.FontSize = Enum.FontSize.Size28
TextButton317.Text = "75%"
TextButton317.TextColor = BrickColor.new("Institutional white")
TextButton317.TextColor3 = Color3.new(1, 1, 1)
TextButton317.TextSize = 26
TextButton317.TextWrap = true
TextButton317.TextWrapped = true
TextButton318.Name = "Button5"
TextButton318.Parent = Frame312
TextButton318.Position = UDim2.new(0, 0, 0.831856549, 0)
TextButton318.Size = UDim2.new(1, 0, 0.00513475854, 35)
TextButton318.BackgroundColor = BrickColor.new("Black metallic")
TextButton318.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton318.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton318.BorderSizePixel = 0
TextButton318.ZIndex = 4
TextButton318.Font = Enum.Font.SourceSans
TextButton318.FontSize = Enum.FontSize.Size28
TextButton318.Text = "150%"
TextButton318.TextColor = BrickColor.new("Institutional white")
TextButton318.TextColor3 = Color3.new(1, 1, 1)
TextButton318.TextSize = 26
TextButton318.TextWrap = true
TextButton318.TextWrapped = true
LocalScript319.Name = "Effect"
LocalScript319.Parent = Frame310
table.insert(cors,sandbox(LocalScript319,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
ImageButton320.Name = "Size"
ImageButton320.Parent = Frame309
ImageButton320.Position = UDim2.new(0.101433806, 0, 0.109531686, 0)
ImageButton320.Size = UDim2.new(0, 12, 0, 12)
ImageButton320.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton320.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton320.BackgroundTransparency = 1
ImageButton320.BorderColor = BrickColor.new("Really black")
ImageButton320.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton320.ZIndex = 999
ImageButton320.Image = "rbxassetid://5761429802"
ImageButton320.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton320.ImageTransparency = 1
TextLabel321.Name = "Size"
TextLabel321.Parent = ImageButton320
TextLabel321.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel321.Size = UDim2.new(0, 324, 0, 20)
TextLabel321.BackgroundColor = BrickColor.new("Institutional white")
TextLabel321.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel321.BackgroundTransparency = 1
TextLabel321.Font = Enum.Font.SourceSans
TextLabel321.FontSize = Enum.FontSize.Size28
TextLabel321.Text = "Menu size"
TextLabel321.TextColor = BrickColor.new("Institutional white")
TextLabel321.TextColor3 = Color3.new(1, 1, 1)
TextLabel321.TextSize = 26
TextLabel321.TextWrap = true
TextLabel321.TextWrapped = true
TextLabel321.TextXAlignment = Enum.TextXAlignment.Left
LocalScript322.Name = "Function"
LocalScript322.Parent = ImageButton320
table.insert(cors,sandbox(LocalScript322,function()
while true do
	wait()
	if script.Parent.Parent.DropDown.Selection.Text ~= "[...]" then
		
		if script.Parent.Parent.DropDown.Selection.Text == ("25%") then
			script.Parent.Parent.Parent.Parent.Parent.Parent.UIScale.Scale = 0.25
		end
		
		if script.Parent.Parent.DropDown.Selection.Text == ("50%") then
		   script.Parent.Parent.Parent.Parent.Parent.Parent.UIScale.Scale = 0.5
		end

		if  script.Parent.Parent.DropDown.Selection.Text == ("75%") then
			script.Parent.Parent.Parent.Parent.Parent.Parent.UIScale.Scale = 0.75
		end

		if  script.Parent.Parent.DropDown.Selection.Text == ("100%") then
			script.Parent.Parent.Parent.Parent.Parent.Parent.UIScale.Scale = 1
		end
		
		if  script.Parent.Parent.DropDown.Selection.Text == ("125%") then
			script.Parent.Parent.Parent.Parent.Parent.Parent.UIScale.Scale = 1.25
		end
		
		if  script.Parent.Parent.DropDown.Selection.Text == ("150%") then
			script.Parent.Parent.Parent.Parent.Parent.Parent.UIScale.Scale = 1.5
		end
	end
end
			
			
			

end))
TextLabel323.Name = "Settings"
TextLabel323.Parent = Frame309
TextLabel323.Position = UDim2.new(0.0361394361, 0, -0.0346901305, 0)
TextLabel323.Size = UDim2.new(0, 97, 0, 10)
TextLabel323.Active = true
TextLabel323.BackgroundColor = BrickColor.new("Really black")
TextLabel323.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel323.BorderColor = BrickColor.new("Really black")
TextLabel323.BorderColor3 = Color3.new(0, 0, 0)
TextLabel323.BorderSizePixel = 0
TextLabel323.ZIndex = 2
TextLabel323.Font = Enum.Font.SourceSansBold
TextLabel323.FontSize = Enum.FontSize.Size28
TextLabel323.Text = "Settings"
TextLabel323.TextColor = BrickColor.new("Mid gray")
TextLabel323.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel323.TextSize = 28
TextLabel323.TextWrap = true
TextLabel323.TextWrapped = true
Frame324.Name = "MiscellaneousTab"
Frame324.Parent = Frame306
Frame324.Position = UDim2.new(0.0236982461, 0, 0.0315125808, 0)
Frame324.Size = UDim2.new(0, 424, 0, 954)
Frame324.BackgroundColor = BrickColor.new("Really black")
Frame324.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame324.BorderColor = BrickColor.new("Dirt brown")
Frame324.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame324.BorderSizePixel = 2
TextLabel325.Name = "Miscellaneous"
TextLabel325.Parent = Frame324
TextLabel325.Position = UDim2.new(0.0361394361, 0, -0.00979359634, 0)
TextLabel325.Size = UDim2.new(0, 151, 0, 10)
TextLabel325.Active = true
TextLabel325.BackgroundColor = BrickColor.new("Really black")
TextLabel325.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel325.BorderColor = BrickColor.new("Really black")
TextLabel325.BorderColor3 = Color3.new(0, 0, 0)
TextLabel325.BorderSizePixel = 0
TextLabel325.ZIndex = 2
TextLabel325.Font = Enum.Font.SourceSansBold
TextLabel325.FontSize = Enum.FontSize.Size28
TextLabel325.Text = "Miscellaneous"
TextLabel325.TextColor = BrickColor.new("Mid gray")
TextLabel325.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel325.TextSize = 28
TextLabel325.TextWrap = true
TextLabel325.TextWrapped = true
ImageButton326.Name = "Crouch"
ImageButton326.Parent = Frame324
ImageButton326.Position = UDim2.new(0.0919999927, 0, 0.293803036, 0)
ImageButton326.Size = UDim2.new(0, 12, 0, 12)
ImageButton326.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton326.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton326.BorderColor = BrickColor.new("Really black")
ImageButton326.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton326.ZIndex = 2
ImageButton326.Image = "rbxassetid://5761429802"
ImageButton326.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton326.ImageTransparency = 0.25
TextLabel327.Name = "Crouch"
TextLabel327.Parent = ImageButton326
TextLabel327.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel327.Size = UDim2.new(0, 324, 0, 20)
TextLabel327.BackgroundColor = BrickColor.new("Institutional white")
TextLabel327.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel327.BackgroundTransparency = 1
TextLabel327.Font = Enum.Font.SourceSans
TextLabel327.FontSize = Enum.FontSize.Size28
TextLabel327.Text = "Infinite crouch"
TextLabel327.TextColor = BrickColor.new("Institutional white")
TextLabel327.TextColor3 = Color3.new(1, 1, 1)
TextLabel327.TextSize = 26
TextLabel327.TextWrap = true
TextLabel327.TextWrapped = true
TextLabel327.TextXAlignment = Enum.TextXAlignment.Left
LocalScript328.Name = "13"
LocalScript328.Parent = ImageButton326
table.insert(cors,sandbox(LocalScript328,function()
local button = script.Parent
local client = getsenv(game.Players.LocalPlayer.PlayerGui.Client)
local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		while toggled==true do
			wait()
			client.crouchcooldown=0
		end

	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
	end
end
button.Activated:Connect(onButtonActivated)




end))
ImageButton329.Name = "Fullauto"
ImageButton329.Parent = Frame324
ImageButton329.Position = UDim2.new(0.0919999927, 0, 0.181571677, 0)
ImageButton329.Size = UDim2.new(0, 12, 0, 12)
ImageButton329.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton329.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton329.BorderColor = BrickColor.new("Really black")
ImageButton329.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton329.ZIndex = 2
ImageButton329.Image = "rbxassetid://5761429802"
ImageButton329.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton329.ImageTransparency = 0.25
TextLabel330.Name = "Fullauto"
TextLabel330.Parent = ImageButton329
TextLabel330.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel330.Size = UDim2.new(0, 324, 0, 20)
TextLabel330.BackgroundColor = BrickColor.new("Institutional white")
TextLabel330.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel330.BackgroundTransparency = 1
TextLabel330.Font = Enum.Font.SourceSans
TextLabel330.FontSize = Enum.FontSize.Size28
TextLabel330.Text = "Automatic weapons"
TextLabel330.TextColor = BrickColor.new("Institutional white")
TextLabel330.TextColor3 = Color3.new(1, 1, 1)
TextLabel330.TextSize = 26
TextLabel330.TextWrap = true
TextLabel330.TextWrapped = true
TextLabel330.TextXAlignment = Enum.TextXAlignment.Left
LocalScript331.Name = "AutoWeapon"
LocalScript331.Parent = ImageButton329
table.insert(cors,sandbox(LocalScript331,function()
local button = script.Parent
local UserInputService = game:GetService("UserInputService")
local toggled = false
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local client = getsenv(plr.PlayerGui.Client)
local plrs = game:GetService("Players")
local mouse = plr.GetMouse()

function coolDown()
	shootCooldown = true
	if game.ReplicatedStorage.Weapons:FindFirstChild(tostring(client.gun)) then
		wait(game.ReplicatedStorage.Weapons:FindFirstChild(tostring(client.gun)).FireRate.Value)
		shootCooldown = false
	end
end

function fireBullet()
	if not shootCooldown then
		client.firebullet()
		coolDown()
	end
end
	
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)	
		mouse.Button1Down:Connect(function()
		while toggled == true do
				wait()
				fireBullet()
		end	
		end)
		

else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
	
		end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton332.Name = "Bhop"
ImageButton332.Parent = Frame324
ImageButton332.Position = UDim2.new(0.0919811353, 0, 0.107163914, 0)
ImageButton332.Size = UDim2.new(0, 12, 0, 12)
ImageButton332.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton332.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton332.BorderColor = BrickColor.new("Really black")
ImageButton332.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton332.ZIndex = 2
ImageButton332.Image = "rbxassetid://5761429802"
ImageButton332.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton332.ImageTransparency = 0.25
TextLabel333.Name = "Bhop"
TextLabel333.Parent = ImageButton332
TextLabel333.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel333.Size = UDim2.new(0, 324, 0, 20)
TextLabel333.BackgroundColor = BrickColor.new("Institutional white")
TextLabel333.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel333.BackgroundTransparency = 1
TextLabel333.Font = Enum.Font.SourceSans
TextLabel333.FontSize = Enum.FontSize.Size28
TextLabel333.Text = "Bunny hop"
TextLabel333.TextColor = BrickColor.new("Institutional white")
TextLabel333.TextColor3 = Color3.new(1, 1, 1)
TextLabel333.TextSize = 26
TextLabel333.TextWrap = true
TextLabel333.TextWrapped = true
TextLabel333.TextXAlignment = Enum.TextXAlignment.Left
LocalScript334.Name = "Bhop"
LocalScript334.Parent = ImageButton332
table.insert(cors,sandbox(LocalScript334,function()
local button = script.Parent
local toggled = false
local val = 0	
local speed = 8

function bhopGYRO()
	down = false		
	local hum = game.Players.LocalPlayer.Character.Humanoid
	function onButton1Down(mouse)
		local uppertorso = game.Players.LocalPlayer.Character.UpperTorso:GetDescendants()
		for i,v in pairs(uppertorso) do
			if v:IsA("BodyVelocity") or v:IsA("BodyGyro") then
				v:Destroy()
			end
		end
		down = true
		velocity = Instance.new("BodyVelocity")
		velocity.Name = "BHOP2"
		velocity.maxForce = Vector3.new(100000, 0, 100000)
		gyro = Instance.new("BodyGyro")
		gyro.maxTorque = Vector3.new(100000, 0, 100000)
		gyro.Name = "BHOP"
		velocity.Parent = game.Players.LocalPlayer.Character.UpperTorso
		velocity.velocity = (hum.MoveDirection) * speed
		gyro.Parent = game.Players.LocalPlayer.Character.UpperTorso
		while down do
			if not down then 
				speed = 8
				break end
			if speed < 50 then
				speed = speed+0.5
			end
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
			velocity.velocity = (hum.MoveDirection) * speed
			local refpos = gyro.Parent.Position + (gyro.Parent.Position - workspace.CurrentCamera.CoordinateFrame.p).unit * 5
			gyro.cframe = CFrame.new(gyro.Parent.Position, Vector3.new(refpos.x, gyro.Parent.Position.y, refpos.z))
			wait()
		end
	end
	function onButton1Up(mouse)
		down = false
		if not down then
			if speed > 0 then
				speed = speed-1
			end
		end
	end
	function onSelected(mouse)
		mouse.KeyDown:connect(function(k) if k:lower()==" "then onButton1Down(mouse)end end)
		mouse.KeyUp:connect(function(k) if k:lower()==" "then onButton1Up(mouse)end end)
	end
	onSelected(game.Players.LocalPlayer:GetMouse())
end

function bhopCFRAME()
	local Players = game:GetService("Players")
	local Player = Players.LocalPlayer
	local userInput = game:service('UserInputService')
	local runService = game:service('RunService')
	local Character = Player.Character
	local pHum = Character.Humanoid
	local humRoot = Character.HumanoidRootPart
	runService.RenderStepped:connect(function()
		if userInput:IsKeyDown(Enum.KeyCode.Space) then
			game.Players.LocalPlayer.Character.Humanoid.Jump = true

			if val < 62 then
				val = val+0.6
			end
		end
		humRoot.CFrame = humRoot.CFrame + pHum.MoveDirection * val/100

		if userInput:IsKeyDown(Enum.KeyCode.Space) == false then
			val = 0
		end
	end)	
end


local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)	
			down = false		
			local hum = game.Players.LocalPlayer.Character.Humanoid
			function onButton1Down(mouse)
				local uppertorso = game.Players.LocalPlayer.Character.UpperTorso:GetDescendants()
				for i,v in pairs(uppertorso) do
					if v:IsA("BodyVelocity") or v:IsA("BodyGyro") then
						v:Destroy()
					end
				end
				down = true
				velocity = Instance.new("BodyVelocity")
				velocity.Name = "BHOP2"
				velocity.maxForce = Vector3.new(100000, 0, 100000)
				gyro = Instance.new("BodyGyro")
				gyro.maxTorque = Vector3.new(100000, 0, 100000)
				gyro.Name = "BHOP"
				velocity.Parent = game.Players.LocalPlayer.Character.UpperTorso
				velocity.velocity = (hum.MoveDirection) * speed
				gyro.Parent = game.Players.LocalPlayer.Character.UpperTorso
				while down do
					if not down then 
						speed = 8
						break end
					if speed < 52 then
						speed = speed+0.5
					end
					game.Players.LocalPlayer.Character.Humanoid.Jump = true
					velocity.velocity = (hum.MoveDirection) * speed
					local refpos = gyro.Parent.Position + (gyro.Parent.Position - workspace.CurrentCamera.CoordinateFrame.p).unit * 5
					gyro.cframe = CFrame.new(gyro.Parent.Position, Vector3.new(refpos.x, gyro.Parent.Position.y, refpos.z))
					wait()
				end
			end
		function onButton1Up(mouse)
			velocity.Parent = nil
			gyro.Parent = nil
			down = false
			speed = 0
			end
			function onSelected(mouse)
				mouse.KeyDown:connect(function(k) if k:lower()==" "then onButton1Down(mouse)end end)
				mouse.KeyUp:connect(function(k) if k:lower()==" "then onButton1Up(mouse)end end)
			end
		onSelected(game.Players.LocalPlayer:GetMouse())	
	while wait() do
		local Player = game:GetService('Players').LocalPlayer
		repeat wait() until Player.CharacterAdded:Wait()
		wait(2)
			local uppertorso = game.Players.LocalPlayer.Character.UpperTorso:GetDescendants()
			for i,v in pairs(uppertorso) do
				if v:IsA("BodyVelocity") or v:IsA("BodyGyro") then
					v:Destroy()
				end
			end
				down = false		
				local hum = game.Players.LocalPlayer.Character.Humanoid
				function onButton1Down(mouse)
					local uppertorso = game.Players.LocalPlayer.Character.UpperTorso:GetDescendants()
					for i,v in pairs(uppertorso) do
						if v:IsA("BodyVelocity") or v:IsA("BodyGyro") then
							v:Destroy()
						end
					end
					down = true
					velocity = Instance.new("BodyVelocity")
					velocity.Name = "BHOP2"
					velocity.maxForce = Vector3.new(100000, 0, 100000)
					gyro = Instance.new("BodyGyro")
					gyro.maxTorque = Vector3.new(100000, 0, 100000)
					gyro.Name = "BHOP"
					velocity.Parent = game.Players.LocalPlayer.Character.UpperTorso
					velocity.velocity = (hum.MoveDirection) * speed
					gyro.Parent = game.Players.LocalPlayer.Character.UpperTorso
					while down do
						if not down then 
							speed = 8
							break end
						if speed < 52 then
							speed = speed+0.5
						end
						game.Players.LocalPlayer.Character.Humanoid.Jump = true
						velocity.velocity = (hum.MoveDirection) * speed
						local refpos = gyro.Parent.Position + (gyro.Parent.Position - workspace.CurrentCamera.CoordinateFrame.p).unit * 5
						gyro.cframe = CFrame.new(gyro.Parent.Position, Vector3.new(refpos.x, gyro.Parent.Position.y, refpos.z))
						wait()
					end
				end
			function onButton1Up(mouse)
					velocity.Parent = nil
					gyro.Parent = nil
					down = false
					speed = 0
				end
				function onSelected(mouse)
					mouse.KeyDown:connect(function(k) if k:lower()==" "then onButton1Down(mouse)end end)
					mouse.KeyUp:connect(function(k) if k:lower()==" "then onButton1Up(mouse)end end)
				end
				onSelected(game.Players.LocalPlayer:GetMouse())		
		end
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		val = 0
		speed = 0
		local uppertorso = game.Players.LocalPlayer.Character.UpperTorso:GetDescendants()
		for i,v in pairs(uppertorso) do
			if v:IsA("BodyVelocity") or v:IsA("BodyGyro") then
				v:Destroy()
			end
		end
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton335.Name = "Spam"
ImageButton335.Parent = Frame324
ImageButton335.Position = UDim2.new(0.0919999927, 0, 0.218980774, 0)
ImageButton335.Size = UDim2.new(0, 12, 0, 12)
ImageButton335.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton335.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton335.BorderColor = BrickColor.new("Really black")
ImageButton335.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton335.ZIndex = 2
ImageButton335.Image = "rbxassetid://5761429802"
ImageButton335.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton335.ImageTransparency = 0.25
TextLabel336.Name = "Chatspam"
TextLabel336.Parent = ImageButton335
TextLabel336.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel336.Size = UDim2.new(0, 324, 0, 20)
TextLabel336.BackgroundColor = BrickColor.new("Institutional white")
TextLabel336.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel336.BackgroundTransparency = 1
TextLabel336.Font = Enum.Font.SourceSans
TextLabel336.FontSize = Enum.FontSize.Size28
TextLabel336.Text = "Spam chat"
TextLabel336.TextColor = BrickColor.new("Institutional white")
TextLabel336.TextColor3 = Color3.new(1, 1, 1)
TextLabel336.TextSize = 26
TextLabel336.TextWrap = true
TextLabel336.TextWrapped = true
TextLabel336.TextXAlignment = Enum.TextXAlignment.Left
LocalScript337.Name = "Spam"
LocalScript337.Parent = ImageButton335
table.insert(cors,sandbox(LocalScript337,function()
local button = script.Parent
local toggled = false

local chatmessages = {
	"p100",
	"hitting big p",
	"ez kills",
	"1'd",
	"u mad??",
	"nn dead",
	"who.ru",
	"bloxsense > all",
	"mad?",
	"did you even execute??",
	"gimmie ur watermelons",
	"a rat with a hdmi port is typing this",	
	"It looks like your face caught on fire and someone tried to put it out with a fork.",
	"Don't you love nature, despite what it did to you?",
}


local function onButtonActivated()
	if toggled == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		toggled = true
		while wait(5) do
			local A_1 = chatmessages[math.random(1,table.getn(chatmessages))]
			local A_2 = false
			local A_3 = "Innocent"
			local A_4 = false
			local A_5 = false
			local Event = game:GetService("ReplicatedStorage").Events.PlayerChatted
			Event:FireServer(A_1, A_2, A_3, A_4, A_5)
		end
	else
		toggled = false
		script.Parent.BackgroundColor3 = Color3.fromRGB(74,74,74)
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton338.Name = "infmoney"
ImageButton338.Parent = Frame324
ImageButton338.Position = UDim2.new(0.0919999927, 0, 0.256389886, 0)
ImageButton338.Size = UDim2.new(0, 12, 0, 12)
ImageButton338.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton338.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton338.BorderColor = BrickColor.new("Really black")
ImageButton338.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton338.ZIndex = 2
ImageButton338.Image = "rbxassetid://5761429802"
ImageButton338.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton338.ImageTransparency = 0.25
TextLabel339.Name = "infmoney"
TextLabel339.Parent = ImageButton338
TextLabel339.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel339.Size = UDim2.new(0, 324, 0, 20)
TextLabel339.BackgroundColor = BrickColor.new("Institutional white")
TextLabel339.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel339.BackgroundTransparency = 1
TextLabel339.Font = Enum.Font.SourceSans
TextLabel339.FontSize = Enum.FontSize.Size28
TextLabel339.Text = "Infinite money"
TextLabel339.TextColor = BrickColor.new("Institutional white")
TextLabel339.TextColor3 = Color3.new(1, 1, 1)
TextLabel339.TextSize = 26
TextLabel339.TextWrap = true
TextLabel339.TextWrapped = true
TextLabel339.TextXAlignment = Enum.TextXAlignment.Left
LocalScript340.Name = "16"
LocalScript340.Parent = ImageButton338
table.insert(cors,sandbox(LocalScript340,function()
local TOGGLED = false
local haha=0
local oldcash=0

script.Parent.MouseButton1Click:Connect(function()
	TOGGLED = not TOGGLED
	if TOGGLED == false then
		script.Parent.BackgroundColor3 = Color3.fromRGB(74,74,74)
	else
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		oldcash=game.Players.LocalPlayer.Cash.Value
	end
end)

while wait() do
	if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
			haha=1
			game.Players.LocalPlayer.Cash.Value = 16000
		else
			if haha==1 then
				haha=0
				game.Players.LocalPlayer.Cash.Value=oldcash
			end
		end
	end




end))
ImageButton341.Name = "God"
ImageButton341.Parent = Frame324
ImageButton341.Position = UDim2.new(0.0919811353, 0, 0.144874588, 0)
ImageButton341.Size = UDim2.new(0, 12, 0, 12)
ImageButton341.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton341.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton341.BorderColor = BrickColor.new("Really black")
ImageButton341.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton341.ZIndex = 2
ImageButton341.Image = "rbxassetid://5761429802"
ImageButton341.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton341.ImageTransparency = 0.25
LocalScript342.Name = "god of gods"
LocalScript342.Parent = ImageButton341
table.insert(cors,sandbox(LocalScript342,function()
local button = script.Parent
local toggled = false
function god()
	local player = game.Players.LocalPlayer
	if player.Character then
		if player.Character:FindFirstChild("Humanoid") then
			player.Character.Humanoid.Name = "1"
		end
		local l = player.Character["1"]:Clone()
		l.Parent = player.Character
		l.Name = "Humanoid"; wait()
		player.Character["1"]:Destroy()
		workspace.CurrentCamera.CameraSubject = player.Character.Humanoid
		player.Character.Animate.Disabled = true; wait()
		player.Character.Animate.Disabled = false
	end
end



local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		god()
			
		else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
	end
end

button.Activated:Connect(onButtonActivated)
	

end))
TextLabel343.Name = "God"
TextLabel343.Parent = ImageButton341
TextLabel343.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel343.Size = UDim2.new(0, 324, 0, 20)
TextLabel343.BackgroundColor = BrickColor.new("Institutional white")
TextLabel343.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel343.BackgroundTransparency = 1
TextLabel343.Font = Enum.Font.SourceSans
TextLabel343.FontSize = Enum.FontSize.Size28
TextLabel343.Text = "God exploit (buggy)"
TextLabel343.TextColor = BrickColor.new("Institutional white")
TextLabel343.TextColor3 = Color3.new(1, 1, 1)
TextLabel343.TextSize = 26
TextLabel343.TextWrap = true
TextLabel343.TextWrapped = true
TextLabel343.TextXAlignment = Enum.TextXAlignment.Left
ImageButton344.Name = "FOV"
ImageButton344.Parent = Frame324
ImageButton344.Position = UDim2.new(0.0919811353, 0, 0.0329994522, 0)
ImageButton344.Size = UDim2.new(0, 12, 0, 12)
ImageButton344.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton344.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton344.BorderColor = BrickColor.new("Really black")
ImageButton344.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton344.ZIndex = 2
ImageButton344.Image = "rbxassetid://5761429802"
ImageButton344.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton344.ImageTransparency = 0.25
TextLabel345.Name = "FOVcontrol"
TextLabel345.Parent = ImageButton344
TextLabel345.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel345.Size = UDim2.new(0, 324, 0, 20)
TextLabel345.BackgroundColor = BrickColor.new("Institutional white")
TextLabel345.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel345.BackgroundTransparency = 1
TextLabel345.Selectable = true
TextLabel345.Font = Enum.Font.SourceSans
TextLabel345.FontSize = Enum.FontSize.Size28
TextLabel345.Text = "Override FOV"
TextLabel345.TextColor = BrickColor.new("Institutional white")
TextLabel345.TextColor3 = Color3.new(1, 1, 1)
TextLabel345.TextSize = 26
TextLabel345.TextWrap = true
TextLabel345.TextWrapped = true
TextLabel345.TextXAlignment = Enum.TextXAlignment.Left
LocalScript346.Name = "5"
LocalScript346.Parent = ImageButton344
table.insert(cors,sandbox(LocalScript346,function()
local button = script.Parent
local toggled = false
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local fovloop

local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		if script.Parent.Parent.Parent.Parent.Parent.Visual.Main.EffectsTab.NoScope.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
			fovloop=game["Run Service"].RenderStepped:Connect(function()
				getsenv(game.Players.LocalPlayer.PlayerGui.Client).fieldofview = tonumber(script.Parent.Parent.Background.Bar.Button.ValueText.Text)
				game.Workspace.CurrentCamera.FieldOfView = tonumber(script.Parent.Parent.Background.Bar.Button.ValueText.Text)
			end)
		else
			fovloop:Disconnect()
			getsenv(game.Players.LocalPlayer.PlayerGui.Client).fieldofview = tonumber(script.Parent.Parent.Background.Bar.Button.ValueText.Text)
			game.Workspace.CurrentCamera.FieldOfView = tonumber(script.Parent.Parent.Background.Bar.Button.ValueText.Text)
		end
		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		game.Workspace.CurrentCamera.FieldOfView = 70
		pcall(function()
		fovloop:Disconnect()
		end)
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton347.Name = "AFK"
ImageButton347.Parent = Frame324
ImageButton347.Position = UDim2.new(0.0920000002, 0, 0.370215952, 0)
ImageButton347.Size = UDim2.new(0, 12, 0, 12)
ImageButton347.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton347.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton347.BorderColor = BrickColor.new("Really black")
ImageButton347.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton347.ZIndex = 2
ImageButton347.Image = "rbxassetid://5761429802"
ImageButton347.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton347.ImageTransparency = 0.25
TextLabel348.Name = "AFK"
TextLabel348.Parent = ImageButton347
TextLabel348.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel348.Size = UDim2.new(0, 324, 0, 20)
TextLabel348.BackgroundColor = BrickColor.new("Institutional white")
TextLabel348.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel348.BackgroundTransparency = 1
TextLabel348.Font = Enum.Font.SourceSans
TextLabel348.FontSize = Enum.FontSize.Size28
TextLabel348.Text = "AFK"
TextLabel348.TextColor = BrickColor.new("Institutional white")
TextLabel348.TextColor3 = Color3.new(1, 1, 1)
TextLabel348.TextSize = 26
TextLabel348.TextWrap = true
TextLabel348.TextWrapped = true
TextLabel348.TextXAlignment = Enum.TextXAlignment.Left
LocalScript349.Name = "3"
LocalScript349.Parent = ImageButton347
table.insert(cors,sandbox(LocalScript349,function()
local button = script.Parent



local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		plr = game:GetService("Players").LocalPlayer
		char = plr.Character
		hum = char:FindFirstChildOfClass'Humanoid'
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		moveChar = coroutine.wrap(function()
			while toggled==true do
				wait(1)
				hum:Move(Vector3.new(22, 0, 0), false)
				wait(1)
				hum:Move(Vector3.new(-22, 0, 0), false)
				wait(1)
				hum:Move(Vector3.new(22, 0, 0), false)
				wait(1)
				hum:Move(Vector3.new(-22, 0, 0), false)
				wait(1)
				hum:Move(Vector3.new(0, 22, 0), false)
				wait(1)
				hum:Move(Vector3.new(0, 22, 0), false)
				wait(5)
			end
		end)
		moveChar()
	else
		toggled = false
		script.Parent.BackgroundColor3 = Color3.fromRGB(74,74,74)
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton350.Name = "Killall"
ImageButton350.Parent = Frame324
ImageButton350.Position = UDim2.new(0.0920000002, 0, 0.40821594, 0)
ImageButton350.Size = UDim2.new(0, 12, 0, 12)
ImageButton350.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton350.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton350.BorderColor = BrickColor.new("Really black")
ImageButton350.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton350.ZIndex = 2
ImageButton350.Image = "rbxassetid://5761429802"
ImageButton350.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton350.ImageTransparency = 0.25
TextLabel351.Name = "Killall"
TextLabel351.Parent = ImageButton350
TextLabel351.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel351.Size = UDim2.new(0, 324, 0, 20)
TextLabel351.BackgroundColor = BrickColor.new("Institutional white")
TextLabel351.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel351.BackgroundTransparency = 1
TextLabel351.Font = Enum.Font.SourceSans
TextLabel351.FontSize = Enum.FontSize.Size28
TextLabel351.Text = "Kill all spammer"
TextLabel351.TextColor = BrickColor.new("Institutional white")
TextLabel351.TextColor3 = Color3.new(1, 1, 1)
TextLabel351.TextSize = 26
TextLabel351.TextWrap = true
TextLabel351.TextWrapped = true
TextLabel351.TextXAlignment = Enum.TextXAlignment.Left
LocalScript352.Name = "fuckall"
LocalScript352.Parent = ImageButton350
table.insert(cors,sandbox(LocalScript352,function()
local button = script.Parent
local toggled = false

function rapeall()
		for _,player in pairs(game:GetService("Players"):GetChildren()) do
			if(player.Team ~= player.Parent.LocalPlayer.Team) then
				if(player.Character and player.Character:FindFirstChild("Head") and player.Parent.LocalPlayer.Character and player.Parent.LocalPlayer.Character:FindFirstChild("EquippedTool")) then
					if(player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.Health > 0) then
						local args = {
							[1] = player.Character.Head,
							[2] = player.Character.Head.Position,
							[3] = player.Parent.LocalPlayer.Character.EquippedTool.Value,
							[4] = math.huge,
							[5] = player.Parent.LocalPlayer.Character.Gun,
							[8] = 2,
							[9] = false,
							[10] = true,
							[11] = Vector3.new(),
							[12] = math.rad(1,100000),
							[13] = Vector3.new()
						}

						game.ReplicatedStorage.Events.HitPart:FireServer(unpack(args))
					end
				end
			end
		end
end


local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		game['Run Service'].RenderStepped:connect(function()
			if toggled == true then
				rapeall()
			end		
		end)
		local Player = game:GetService('Players').LocalPlayer
		Player.CharacterAdded:Wait()
		game['Run Service'].RenderStepped:connect(function()
		if toggled == true then
			rapeall()
		end
		end)
	
	else	
		toggled = false
		script.Parent.BackgroundColor3 = Color3.fromRGB(74,74,74)
	end
end

		
button.Activated:Connect(onButtonActivated)	
	





end))
ImageButton353.Name = "WaterMark"
ImageButton353.Parent = Frame324
ImageButton353.Position = UDim2.new(0.0920000002, 0, 0.446215957, 0)
ImageButton353.Size = UDim2.new(0, 12, 0, 12)
ImageButton353.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton353.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton353.BorderColor = BrickColor.new("Really black")
ImageButton353.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton353.ZIndex = 2
ImageButton353.Image = "rbxassetid://5761429802"
ImageButton353.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton353.ImageTransparency = 0.25
TextLabel354.Name = "Watermark"
TextLabel354.Parent = ImageButton353
TextLabel354.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel354.Size = UDim2.new(0, 324, 0, 20)
TextLabel354.BackgroundColor = BrickColor.new("Institutional white")
TextLabel354.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel354.BackgroundTransparency = 1
TextLabel354.ZIndex = 999999999
TextLabel354.Font = Enum.Font.SourceSans
TextLabel354.FontSize = Enum.FontSize.Size28
TextLabel354.Text = "Watermark"
TextLabel354.TextColor = BrickColor.new("Institutional white")
TextLabel354.TextColor3 = Color3.new(1, 1, 1)
TextLabel354.TextSize = 26
TextLabel354.TextWrap = true
TextLabel354.TextWrapped = true
TextLabel354.TextXAlignment = Enum.TextXAlignment.Left
LocalScript355.Name = "15"
LocalScript355.Parent = ImageButton353
table.insert(cors,sandbox(LocalScript355,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.Watermark.Visible = true
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.Watermark.Visible = false
	end
end
button.Activated:Connect(onButtonActivated)
end))
ImageButton356.Name = "Tag"
ImageButton356.Parent = Frame324
ImageButton356.Position = UDim2.new(0.0920000002, 0, 0.484215945, 0)
ImageButton356.Size = UDim2.new(0, 12, 0, 12)
ImageButton356.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton356.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton356.BorderColor = BrickColor.new("Really black")
ImageButton356.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton356.ZIndex = 2
ImageButton356.Image = "rbxassetid://5761429802"
ImageButton356.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton356.ImageTransparency = 0.25
TextLabel357.Name = "tag"
TextLabel357.Parent = ImageButton356
TextLabel357.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel357.Size = UDim2.new(0, 324, 0, 20)
TextLabel357.BackgroundColor = BrickColor.new("Institutional white")
TextLabel357.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel357.BackgroundTransparency = 1
TextLabel357.ZIndex = 999999999
TextLabel357.Font = Enum.Font.SourceSans
TextLabel357.FontSize = Enum.FontSize.Size28
TextLabel357.Text = "Tags"
TextLabel357.TextColor = BrickColor.new("Institutional white")
TextLabel357.TextColor3 = Color3.new(1, 1, 1)
TextLabel357.TextSize = 26
TextLabel357.TextWrap = true
TextLabel357.TextWrapped = true
TextLabel357.TextXAlignment = Enum.TextXAlignment.Left
LocalScript358.Name = "BS"
LocalScript358.Parent = ImageButton356
table.insert(cors,sandbox(LocalScript358,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.tags.Visible = true

	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.tags.Visible = false
	end
end
button.Activated:Connect(onButtonActivated)




end))
ImageButton359.Name = "Ragequit"
ImageButton359.Parent = Frame324
ImageButton359.Position = UDim2.new(0.193386719, 0, 0.518588603, 0)
ImageButton359.Size = UDim2.new(0, 259, 0, 31)
ImageButton359.BackgroundColor = BrickColor.new("Black")
ImageButton359.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
ImageButton359.BorderColor = BrickColor.new("Really black")
ImageButton359.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton359.BorderSizePixel = 3
ImageButton359.ZIndex = 2
ImageButton359.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton359.ImageTransparency = 0.25
TextLabel360.Name = "Ragequit"
TextLabel360.Parent = ImageButton359
TextLabel360.Position = UDim2.new(0, 0, 0.333333343, -6)
TextLabel360.Size = UDim2.new(0, 258, 0, 20)
TextLabel360.BackgroundColor = BrickColor.new("Institutional white")
TextLabel360.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel360.BackgroundTransparency = 1
TextLabel360.ZIndex = 3
TextLabel360.Font = Enum.Font.SourceSans
TextLabel360.FontSize = Enum.FontSize.Size28
TextLabel360.Text = "Rage quit"
TextLabel360.TextColor = BrickColor.new("Institutional white")
TextLabel360.TextColor3 = Color3.new(1, 1, 1)
TextLabel360.TextSize = 26
TextLabel360.TextWrap = true
TextLabel360.TextWrapped = true
LocalScript361.Name = "RQ"
LocalScript361.Parent = ImageButton359
table.insert(cors,sandbox(LocalScript361,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		local v2
		local m = math.random(1,50)
		
		if m == 1 then
			v2 = "Well, that happend."
		end
		if m == 2 then
			v2 = "OOF"
		end
		if m == 3 then
			v2 = "Ouchies."
		end
		if m == 4 then
			v2 = "u mad?"
		end
		if m == 5 then
			v2 = "Practice makes perfect."
		end
		if m == 6 then
			v2 = "Did you mean to do that?"
		end
		if m == 7 then
			v2 = "Don't do that again."
		end
		if m == 8 then
			v2 = "Bada ba ba ba, I'm lovin' it."
		end
		if m == 9 then
			v2 = "How'd that happen?"
		end
		if m == 10 then
			v2 = "Sʇod ʇʍᴉsʇᴉuƃ ʎonɹ ɥǝɐp˙"
		end
		if m == 11 then
			v2 = "Well, that happend."
		end
		if m == 12 then
			v2 = "yeah ok"
		end
		if m == 13 then
			v2 = "Tip : stop clicking this"
		end
		if m == 14 then
			v2 = "Tip : This button doesn't relieve rage, for some reason."
		end
		if m == 15 then
			v2 = "why do you find the need to press that button"
		end
		if m == 16 then
			v2 = "Tip : Don't rage."
		end
		if m == 17 then
			v2 = "Mada mada."
		end
		if m == 18 then
			v2 = "VCMYXC1RiQVoUHWoKPSROQ=="
		end
		if m == 19 then
			v2 = "Hack the game"
		end
		if m == 20 then
			v2 = "Error 404 : Rage quit message not found."
		end
		if m == 21 then
			v2 = "<Insert rage quit message here>"
		end
		if m == 22 then
			v2 = "Sweet rage bro!!"
		end
		if m == 23 then
			v2 = "Whos that behind you?"
		end
		if m == 24 then
			v2 = "Oh, So close!"
		end
		if m == 25 then
			v2 = "Nope."
		end
		if m == 26 then
			v2 = "Undo!"
		end
		if m == 27 then
			v2 = "Is that a jojo reference?"
		end
		if m == 28 then
			v2 = "AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHH..."
		end
		if m == 29 then
			v2 = "Stop screwing around!"
		end
		if m == 30 then
			v2 = "useless button rite ;/"
		end
		if m == 31 then
			v2 = "?????"
		end
		if m == 32 then
			v2 = "That wasn't the plan."
		end
		if m == 33 then
			v2 = "???????????"
		end
		if m == 34 then
			v2 = "nice one"
		end
		if m == 35 then
			v2 = "whats 4 squared?"
		end
		if m == 36 then
			v2 = "Don't lose your head."
		end
		if m == 37 then
			v2 = "Stimulate your senses."
		end
		if m == 38 then
			v2 = "Don't clip that."
		end
		if m == 39 then
			v2 = "Kappa."
		end
		if m == 40 then
			v2 = "OwO Wuts dis?" 
		end
		if m == 41 then
			v2 = "Try again." 
		end
		if m == 41 then
			v2 = "Game over!" 
		end
		if m == 42 then
			v2 = "Why?" 
		end
		if m == 43 then
			v2 = "Stop rage quitting" 
		end
		if m == 44 then
			v2 = "Are you angry yet?" 
		end
		if m == 45 then
			v2 = "I've got 99 problems, This cheat aint one" 
		end
		if m == 46 then
			v2 = "Huh? What happend?" 
		end
		if m == 47 then
			v2 = "Where'd you go?" 
		end
		if m == 48 then
			v2 = "Don't rage quit again." 
		end
		if m == 49 then
			v2 = "No..." 
		if m == 50 then
			v2 = "Did you rage quit again?" 
		end
		end
		
game.Players.LocalPlayer:Kick(v2)
	
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
	end
end
button.Activated:Connect(onButtonActivated)


end))
ImageButton362.Name = "Crashgame"
ImageButton362.Parent = Frame324
ImageButton362.Position = UDim2.new(0.193000078, 0, 0.60838908, 0)
ImageButton362.Size = UDim2.new(0, 259, 0, 31)
ImageButton362.BackgroundColor = BrickColor.new("Black")
ImageButton362.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
ImageButton362.BorderColor = BrickColor.new("Really black")
ImageButton362.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton362.BorderSizePixel = 3
ImageButton362.ZIndex = 2
ImageButton362.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton362.ImageTransparency = 0.25
TextLabel363.Name = "Crashgame"
TextLabel363.Parent = ImageButton362
TextLabel363.Position = UDim2.new(0, 0, 0.333333343, -6)
TextLabel363.Size = UDim2.new(0, 258, 0, 20)
TextLabel363.BackgroundColor = BrickColor.new("Institutional white")
TextLabel363.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel363.BackgroundTransparency = 1
TextLabel363.ZIndex = 999999999
TextLabel363.Font = Enum.Font.SourceSans
TextLabel363.FontSize = Enum.FontSize.Size28
TextLabel363.Text = "Crash server"
TextLabel363.TextColor = BrickColor.new("Institutional white")
TextLabel363.TextColor3 = Color3.new(1, 1, 1)
TextLabel363.TextSize = 26
TextLabel363.TextWrap = true
TextLabel363.TextWrapped = true
LocalScript364.Name = "4"
LocalScript364.Parent = ImageButton362
table.insert(cors,sandbox(LocalScript364,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		
		while toggled == true do
			
			wait(3)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				local oh3 = 25
				local oh4 = 35
				local oh6 = ""
				local oh7 = ""
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Molotov"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["HE Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
				game:GetService("ReplicatedStorage").Events.ThrowGrenade:FireServer(game:GetService("ReplicatedStorage").Weapons["Decoy Grenade"].Model, nil, oh3, oh4, Vector3.new(0,-100,0), oh6, oh7)
			end)
		end
		

	
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		
	end
end
button.Activated:Connect(onButtonActivated)
end))
ImageButton365.Name = "Skin"
ImageButton365.Parent = Frame324
ImageButton365.Position = UDim2.new(0.193000078, 0, 0.563488841, 0)
ImageButton365.Size = UDim2.new(0, 259, 0, 31)
ImageButton365.BackgroundColor = BrickColor.new("Black")
ImageButton365.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
ImageButton365.BorderColor = BrickColor.new("Really black")
ImageButton365.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton365.BorderSizePixel = 3
ImageButton365.ZIndex = 2
ImageButton365.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton365.ImageTransparency = 0.25
TextLabel366.Name = "Crash Server"
TextLabel366.Parent = ImageButton365
TextLabel366.Position = UDim2.new(0.00732044829, 0, 0.333001018, -6)
TextLabel366.Size = UDim2.new(0, 257, 0, 20)
TextLabel366.BackgroundColor = BrickColor.new("Institutional white")
TextLabel366.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel366.BackgroundTransparency = 1
TextLabel366.ZIndex = 3
TextLabel366.Font = Enum.Font.SourceSans
TextLabel366.FontSize = Enum.FontSize.Size28
TextLabel366.Text = "Unlock inventory"
TextLabel366.TextColor = BrickColor.new("Institutional white")
TextLabel366.TextColor3 = Color3.new(1, 1, 1)
TextLabel366.TextSize = 26
TextLabel366.TextWrap = true
TextLabel366.TextWrapped = true
LocalScript367.Name = "InvUnlock"
LocalScript367.Parent = ImageButton365
table.insert(cors,sandbox(LocalScript367,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(44, 44, 44)

		local LocalPlayer = game:GetService("Players").LocalPlayer
		local Client = getsenv(game.Players.LocalPlayer.PlayerGui.Client)
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		
		local allSkins = {
			{'AK47_Ace'},
			{'AK47_Bloodboom'},
			{'AK47_Clown'},
			{'AK47_Code Orange'},
			{'AK47_Eve'},
			{'AK47_Gifted'},
			{'AK47_Glo'},
			{'AK47_Godess'},
			{'AK47_Hallows'},
			{'AK47_Halo'},
			{'AK47_Hypersonic'},
			{'AK47_Inversion'},
			{'AK47_Jester'},
			{'AK47_Maker'},
			{'AK47_Mean Green'},
			{'AK47_Outlaws'},
			{'AK47_Outrunner'},
			{'AK47_Patch'},
			{'AK47_Plated'},
			{'AK47_Precision'},
			{'AK47_Quantum'},
			{'AK47_Quicktime'},
			{'AK47_Scapter'},
			{'AK47_Secret Santa'},
			{'AK47_Shooting Star'},
			{'AK47_Skin Committee'},
			{'AK47_Survivor'},
			{'AK47_Ugly Sweater'},
			{'AK47_VAV'},
			{'AK47_Variant Camo'},
			{'AK47_Yltude'},
			{'AUG_Chilly Night'},
			{'AUG_Dream Hound'},
			{'AUG_Enlisted'},
			{'AUG_Graffiti'},
			{'AUG_Homestead'},
			{'AUG_Maker'},
			{'AUG_NightHawk'},
			{'AUG_Phoenix'},
			{'AUG_Sunsthetic'},
			{'AWP_Abaddon'},
			{'AWP_Autumness'},
			{'AWP_Blastech'},
			{'AWP_Bloodborne'},
			{'AWP_Coffin Biter'},
			{'AWP_Desert Camo'},
			{'AWP_Difference'},
			{'AWP_Dragon'},
			{'AWP_Forever'},
			{'AWP_Grepkin'},
			{'AWP_Hika'},
			{'AWP_Illusion'},
			{'AWP_Instinct'},
			{'AWP_JTF2'},
			{'AWP_Lunar'},
			{'AWP_Nerf'},
			{'AWP_Northern Lights'},
			{'AWP_Pear Tree'},
			{'AWP_Pink Vision'},
			{'AWP_Pinkie'},
			{'AWP_Quicktime'},
			{'AWP_Racer'},
			{'AWP_Regina'},
			{'AWP_Retroactive'},
			{'AWP_Scapter'},
			{'AWP_Silence'},
			{'AWP_Venomus'},
			{'AWP_Weeb'},
			{'Banana_Stock'},
			{'Bayonet_Aequalis'},
			{'Bayonet_Banner'},
			{'Bayonet_Candy Cane'},
			{'Bayonet_Consumed'},
			{'Bayonet_Cosmos'},
			{'Bayonet_Crimson Tiger'},
			{'Bayonet_Crow'},
			{'Bayonet_Delinquent'},
			{'Bayonet_Digital'},
			{'Bayonet_Easy-Bake'},
			{'Bayonet_Egg Shell'},
			{'Bayonet_Festive'},
			{'Bayonet_Frozen Dream'},
			{'Bayonet_Geo Blade'},
			{'Bayonet_Ghastly'},
			{'Bayonet_Goo'},
			{'Bayonet_Hallows'},
			{'Bayonet_Intertwine'},
			{'Bayonet_Marbleized'},
			{'Bayonet_Mariposa'},
			{'Bayonet_Naval'},
			{'Bayonet_Neonic'},
			{'Bayonet_RSL'},
			{'Bayonet_Racer'},
			{'Bayonet_Sapphire'},
			{'Bayonet_Silent Night'},
			{'Bayonet_Splattered'},
			{'Bayonet_Stock'},
			{'Bayonet_Topaz'},
			{'Bayonet_Tropical'},
			{'Bayonet_Twitch'},
			{'Bayonet_UFO'},
			{'Bayonet_Wetland'},
			{'Bayonet_Worn'},
			{'Bayonet_Wrapped'},
			{'Bearded Axe_Beast'},
			{'Bearded Axe_Splattered'},
			{'Bizon_Autumic'},
			{'Bizon_Festive'},
			{'Bizon_Oblivion'},
			{'Bizon_Saint Nick'},
			{'Bizon_Sergeant'},
			{'Bizon_Shattered'},
			{'Butterfly Knife_Aurora'},
			{'Butterfly Knife_Bloodwidow'},
			{'Butterfly Knife_Consumed'},
			{'Butterfly Knife_Cosmos'},
			{'Butterfly Knife_Crimson Tiger'},
			{'Butterfly Knife_Crippled Fade'},
			{'Butterfly Knife_Digital'},
			{'Butterfly Knife_Egg Shell'},
			{'Butterfly Knife_Freedom'},
			{'Butterfly Knife_Frozen Dream'},
			{'Butterfly Knife_Goo'},
			{'Butterfly Knife_Hallows'},
			{'Butterfly Knife_Icicle'},
			{'Butterfly Knife_Inversion'},
			{'Butterfly Knife_Jade Dream'},
			{'Butterfly Knife_Marbleized'},
			{'Butterfly Knife_Naval'},
			{'Butterfly Knife_Neonic'},
			{'Butterfly Knife_Reaper'},
			{'Butterfly Knife_Ruby'},
			{'Butterfly Knife_Scapter'},
			{'Butterfly Knife_Splattered'},
			{'Butterfly Knife_Stock'},
			{'Butterfly Knife_Topaz'},
			{'Butterfly Knife_Tropical'},
			{'Butterfly Knife_Twitch'},
			{'Butterfly Knife_Wetland'},
			{'Butterfly Knife_White Boss'},
			{'Butterfly Knife_Worn'},
			{'Butterfly Knife_Wrapped'},
			{'CZ_Designed'},
			{'CZ_Festive'},
			{'CZ_Holidays'},
			{'CZ_Lightning'},
			{'CZ_Orange Web'},
			{'CZ_Spectre'},
			{'Cleaver_Spider'},
			{'Cleaver_Splattered'},
			{'DesertEagle_Cold Truth'},
			{'DesertEagle_Cool Blue'},
			{'DesertEagle_DropX'},
			{'DesertEagle_Glittery'},
			{'DesertEagle_Grim'},
			{'DesertEagle_Heat'},
			{'DesertEagle_Honor-bound'},
			{'DesertEagle_Independence'},
			{'DesertEagle_Krystallos'},
			{'DesertEagle_Pumpkin Buster'},
			{'DesertEagle_ROLVe'},
			{'DesertEagle_Cringe'},
			{'DesertEagle_Racer'},
			{'DesertEagle_Scapter'},
			{'DesertEagle_Skin Committee'},
			{'DesertEagle_Survivor'},
			{'DesertEagle_Weeb'},
			{'DesertEagle_Xmas'},
			{'DualBerettas_Carbonized'},
			{'DualBerettas_Dusty Manor'},
			{'DualBerettas_Floral'},
			{'DualBerettas_Hexline'},
			{'DualBerettas_Neon web'},
			{'DualBerettas_Old Fashioned'},
			{'DualBerettas_Xmas'},
			{'Falchion Knife_Bloodwidow'},
			{'Falchion Knife_Chosen'},
			{'Falchion Knife_Coal'},
			{'Falchion Knife_Consumed'},
			{'Falchion Knife_Cosmos'},
			{'Falchion Knife_Crimson Tiger'},
			{'Falchion Knife_Crippled Fade'},
			{'Falchion Knife_Digital'},
			{'Falchion Knife_Egg Shell'},
			{'Falchion Knife_Festive'},
			{'Falchion Knife_Freedom'},
			{'Falchion Knife_Frozen Dream'},
			{'Falchion Knife_Goo'},
			{'Falchion Knife_Hallows'},
			{'Falchion Knife_Inversion'},
			{'Falchion Knife_Late Night'},
			{'Falchion Knife_Marbleized'},
			{'Falchion Knife_Naval'},
			{'Falchion Knife_Neonic'},
			{'Falchion Knife_Racer'},
			{'Falchion Knife_Ruby'},
			{'Falchion Knife_Splattered'},
			{'Falchion Knife_Stock'},
			{'Falchion Knife_Topaz'},
			{'Falchion Knife_Tropical'},
			{'Falchion Knife_Wetland'},
			{'Falchion Knife_Worn'},
			{'Falchion Knife_Wrapped'},
			{'Falchion Knife_Zombie'},
			{'Famas_Abstract'},
			{'Famas_Centipede'},
			{'Famas_Cogged'},
			{'Famas_Goliath'},
			{'Famas_Haunted Forest'},
			{'Famas_KugaX'},
			{'Famas_MK11'},
			{'Famas_Medic'},
			{'Famas_Redux'},
			{'Famas_Shocker'},
			{'Famas_Toxic Rain'},
			{'FiveSeven_Autumn Fade'},
			{'FiveSeven_Danjo'},
			{'FiveSeven_Fluid'},
			{'FiveSeven_Gifted'},
			{'FiveSeven_Midnight Ride'},
			{'FiveSeven_Mr. Anatomy'},
			{'FiveSeven_Stigma'},
			{'FiveSeven_Sub Zero'},
			{'FiveSeven_Summer'},
			{'Flip Knife_Stock'},
			{'G3SG1_Amethyst'},
			{'G3SG1_Autumn'},
			{'G3SG1_Foliage'},
			{'G3SG1_Hex'},
			{'G3SG1_Holly Bound'},
			{'G3SG1_Mahogany'},
			{'Galil_Frosted'},
			{'Galil_Hardware 2'},
			{'Galil_Hardware'},
			{'Galil_Toxicity'},
			{'Galil_Worn'},
			{'Glock_Angler'},
			{'Glock_Anubis'},
			{'Glock_Biotrip'},
			{'Glock_Day Dreamer'},
			{'Glock_Desert Camo'},
			{'Glock_Gravestomper'},
			{'Glock_Midnight Tiger'},
			{'Glock_Money Maker'},
			{'Glock_RSL'},
			{'Glock_Rush'},
			{'Glock_Scapter'},
			{'Glock_Spacedust'},
			{'Glock_Tarnish'},
			{'Glock_Underwater'},
			{'Glock_Wetland'},
			{'Glock_White Sauce'},
			{'Gut Knife_Banner'},
			{'Gut Knife_Bloodwidow'},
			{'Gut Knife_Consumed'},
			{'Gut Knife_Cosmos'},
			{'Gut Knife_Crimson Tiger'},
			{'Gut Knife_Crippled Fade'},
			{'Gut Knife_Digital'},
			{'Gut Knife_Egg Shell'},
			{'Gut Knife_Frozen Dream'},
			{'Gut Knife_Geo Blade'},
			{'Gut Knife_Goo'},
			{'Gut Knife_Hallows'},
			{'Gut Knife_Lurker'},
			{'Gut Knife_Marbleized'},
			{'Gut Knife_Naval'},
			{'Gut Knife_Neonic'},
			{'Gut Knife_Present'},
			{'Gut Knife_Ruby'},
			{'Gut Knife_Rusty'},
			{'Gut Knife_Splattered'},
			{'Gut Knife_Topaz'},
			{'Gut Knife_Tropical'},
			{'Gut Knife_Wetland'},
			{'Gut Knife_Worn'},
			{'Gut Knife_Wrapped'},
			{'Huntsman Knife_Aurora'},
			{'Huntsman Knife_Bloodwidow'},
			{'Huntsman Knife_Consumed'},
			{'Huntsman Knife_Cosmos'},
			{'Huntsman Knife_Cozy'},
			{'Huntsman Knife_Crimson Tiger'},
			{'Huntsman Knife_Crippled Fade'},
			{'Huntsman Knife_Digital'},
			{'Huntsman Knife_Egg Shell'},
			{'Huntsman Knife_Frozen Dream'},
			{'Huntsman Knife_Geo Blade'},
			{'Huntsman Knife_Goo'},
			{'Huntsman Knife_Hallows'},
			{'Huntsman Knife_Honor Fade'},
			{'Huntsman Knife_Marbleized'},
			{'Huntsman Knife_Monster'},
			{'Huntsman Knife_Naval'},
			{'Huntsman Knife_Ruby'},
			{'Huntsman Knife_Splattered'},
			{'Huntsman Knife_Stock'},
			{'Huntsman Knife_Tropical'},
			{'Huntsman Knife_Twitch'},
			{'Huntsman Knife_Wetland'},
			{'Huntsman Knife_Worn'},
			{'Huntsman Knife_Wrapped'},
			{'Karambit_Bloodwidow'},
			{'Karambit_Consumed'},
			{'Karambit_Cosmos'},
			{'Karambit_Crimson Tiger'},
			{'Karambit_Crippled Fade'},
			{'Karambit_Death Wish'},
			{'Karambit_Digital'},
			{'Karambit_Egg Shell'},
			{'Karambit_Festive'},
			{'Karambit_Frozen Dream'},
			{'Karambit_Glossed'},
			{'Karambit_Gold'},
			{'Karambit_Goo'},
			{'Karambit_Hallows'},
			{'Karambit_Jade Dream'},
			{'Karambit_Jester'},
			{'Karambit_Lantern'},
			{'Karambit_Liberty Camo'},
			{'Karambit_Marbleized'},
			{'Karambit_Naval'},
			{'Karambit_Neonic'},
			{'Karambit_Pizza'},
			{'Karambit_Quicktime'},
			{'Karambit_Racer'},
			{'Karambit_Ruby'},
			{'Karambit_Scapter'},
			{'Karambit_Splattered'},
			{'Karambit_Stock'},
			{'Karambit_Topaz'},
			{'Karambit_Tropical'},
			{'Karambit_Twitch'},
			{'Karambit_Wetland'},
			{'Karambit_Worn'},
			{'M249_Aggressor'},
			{'M249_P2020'},
			{'M249_Spooky'},
			{'M249_Wolf'},
			{'M4A1_Animatic'},
			{'M4A1_Burning'},
			{'M4A1_Desert Camo'},
			{'M4A1_Heavens Gate'},
			{'M4A1_Impulse'},
			{'M4A1_Jester'},
			{'M4A1_Lunar'},
			{'M4A1_Necropolis'},
			{'M4A1_Tecnician'},
			{'M4A1_Toucan'},
			{'M4A1_Wastelander'},
			{'M4A4_BOT[S]'},
			{'M4A4_Candyskull'},
			{'M4A4_Delinquent'},
			{'M4A4_Desert Camo'},
			{'M4A4_Devil'},
			{'M4A4_Endline'},
			{'M4A4_Flashy Ride'},
			{'M4A4_Ice Cap'},
			{'M4A4_Jester'},
			{'M4A4_King'},
			{'M4A4_Mistletoe'},
			{'M4A4_Pinkie'},
			{'M4A4_Pinkvision'},
			{'M4A4_Pondside'},
			{'M4A4_Precision'},
			{'M4A4_Quicktime'},
			{'M4A4_Racer'},
			{'M4A4_RayTrack'},
			{'M4A4_Scapter'},
			{'M4A4_Stardust'},
			{'M4A4_Toy Soldier'},
			{'MAC10_Artists Intent'},
			{'MAC10_Blaze'},
			{'MAC10_Golden Rings'},
			{'MAC10_Pimpin'},
			{'MAC10_Skeleboney'},
			{'MAC10_Toxic'},
			{'MAC10_Turbo'},
			{'MAC10_Wetland'},
			{'MAG7_Bombshell'},
			{'MAG7_C4UTION'},
			{'MAG7_Frosty'},
			{'MAG7_Molten'},
			{'MAG7_Outbreak'},
			{'MAG7_Striped'},
			{'MP7_Calaxian'},
			{'MP7_Cogged'},
			{'MP7_Goo'},
			{'MP7_Holiday'},
			{'MP7_Industrial'},
			{'MP7_Reindeer'},
			{'MP7_Silent Ops'},
			{'MP7_Sunshot'},
			{'MP9_Blueroyal'},
			{'MP9_Cob Web'},
			{'MP9_Cookie Man'},
			{'MP9_Decked Halls'},
			{'MP9_SnowTime'},
			{'MP9_Vaporwave'},
			{'MP9_Velvita'},
			{'MP9_Wilderness'},
			{'Negev_Default'},
			{'Negev_Midnightbones'},
			{'Negev_Quazar'},
			{'Negev_Striped'},
			{'Negev_Wetland'},
			{'Negev_Winterfell'},
			{'Nova_Black Ice'},
			{'Nova_Cookie'},
			{'Nova_Paradise'},
			{'Nova_Sharkesh'},
			{'Nova_Starry Night'},
			{'Nova_Terraformer'},
			{'Nova_Tiger'},
			{'P2000_Apathy'},
			{'P2000_Camo Dipped'},
			{'P2000_Candycorn'},
			{'P2000_Comet'},
			{'P2000_Dark Beast'},
			{'P2000_Golden Age'},
			{'P2000_Lunar'},
			{'P2000_Pinkie'},
			{'P2000_Ruby'},
			{'P2000_Silence'},
			{'P250_Amber'},
			{'P250_Bomber'},
			{'P250_Equinox'},
			{'P250_Frosted'},
			{'P250_Goldish'},
			{'P250_Green Web'},
			{'P250_Shark'},
			{'P250_Solstice'},
			{'P250_TC250'},
			{'P90_Demon Within'},
			{'P90_Elegant'},
			{'P90_Krampus'},
			{'P90_Northern Lights'},
			{'P90_P-Chan'},
			{'P90_Pine'},
			{'P90_Redcopy'},
			{'P90_Skulls'},
			{'R8_Exquisite'},
			{'R8_Hunter'},
			{'R8_Spades'},
			{'R8_TG'},
			{'R8_Violet'},
			{'SG_DropX'},
			{'SG_Dummy'},
			{'SG_Kitty Cat'},
			{'SG_Knighthood'},
			{'SG_Magma'},
			{'SG_Variant Camo'},
			{'SG_Yltude'},
			{'SawedOff_Casino'},
			{'SawedOff_Colorboom'},
			{'SawedOff_Executioner'},
			{'SawedOff_Opal'},
			{'SawedOff_Spooky'},
			{'SawedOff_Sullys Blacklight'},
			{'Scout_Coffin Biter'},
			{'Scout_Flowing Mists'},
			{'Scout_Hellborn'},
			{'Scout_Hot Cocoa'},
			{'Scout_Monstruo'},
			{'Scout_Neon Regulation'},
			{'Scout_Posh'},
			{'Scout_Pulse'},
			{'Scout_Railgun'},
			{'Scout_Theory'},
			{'Scout_Xmas'},
			{'Sickle_Mummy'},
			{'Sickle_Splattered'},
			{'Tec9_Charger'},
			{'Tec9_Gift Wrapped'},
			{'Tec9_Ironline'},
			{'Tec9_Performer'},
			{'Tec9_Phol'},
			{'Tec9_Samurai'},
			{'Tec9_Skintech'},
			{'Tec9_Stocking Stuffer'},
			{'UMP_Death Grip'},
			{'UMP_Gum Drop'},
			{'UMP_Magma'},
			{'UMP_Militia Camo'},
			{'UMP_Molten'},
			{'UMP_Redline'},
			{'USP_Crimson'},
			{'USP_Dizzy'},
			{'USP_Frostbite'},
			{'USP_Holiday'},
			{'USP_Jade Dream'},
			{'USP_Kraken'},
			{'USP_Nighttown'},
			{'USP_Paradise'},
			{'USP_Racing'},
			{'USP_Skull'},
			{'USP_Unseen'},
			{'USP_Worlds Away'},
			{'USP_Yellowbelly'},
			{'XM_Artic'},
			{'XM_Atomic'},
			{'XM_Campfire'},
			{'XM_Endless Night'},
			{'XM_MK11'},
			{'XM_Predator'},
			{'XM_Red'},
			{'XM_Spectrum'},
			{'Handwraps_Wraps'},
			{'Sports Glove_Hazard'},
			{'Sports Glove_Hallows'},
			{'Sports Glove_Majesty'},
			{'Strapped Glove_Racer'},
			{'Strapped Glove_Grim'},
			{'Strapped Glove_Wisk'},
			{'Fingerless Glove_Scapter'},
			{'Fingerless Glove_Digital'},
			{'Fingerless Glove_Patch'},
			{'Handwraps_Guts'},
			{'Handwraps_Wetland'},
			{'Strapped Glove_Molten'},
			{'Fingerless Glove_Crystal'},
			{'Sports Glove_Royal'},
			{'Strapped Glove_Kringle'},
			{'Handwraps_MMA'},
			{'Sports Glove_Weeb'},
			{'Sports Glove_CottonTail'},
			{'Sports Glove_RSL'},
			{'Handwraps_Ghoul Hex'},
			{'Handwraps_Phantom Hex'},
			{'Handwraps_Spector Hex'},
			{'Handwraps_Orange Hex'},
			{'Handwraps_Purple Hex'},
			{'Handwraps_Green Hex'},
		}
		
		local isUnlocked
		
		local mt = getrawmetatable(game)
		local oldNamecall = mt.__namecall
		setreadonly(mt, false)
		
		local isUnlocked
		
		mt.__namecall = newcclosure(function(self, ...)
			local args = {...}
			if getnamecallmethod() == "InvokeServer" and tostring(self) == "Hugh" then
				return
			end
			if getnamecallmethod() == "FireServer" then
				if args[1] == LocalPlayer.UserId then
					return
				end
				if string.len(tostring(self)) == 38 then
					if not isUnlocked then
						isUnlocked = true
						for i,v in pairs(allSkins) do
							local doSkip
							for i2,v2 in pairs(args[1]) do
								if v[1] == v2[1] then
									doSkip = true
								end
							end
							if not doSkip then
								table.insert(args[1], v)
							end
						end
					end
					return
				end
				if tostring(self) == "DataEvent" and args[1][4] then
					local currentSkin = string.split(args[1][4][1], "_")[2]
					if args[1][2] == "Both" then
						LocalPlayer["SkinFolder"]["CTFolder"][args[1][3]].Value = currentSkin
						LocalPlayer["SkinFolder"]["TFolder"][args[1][3]].Value = currentSkin
					else
						LocalPlayer["SkinFolder"][args[1][2] .. "Folder"][args[1][3]].Value = currentSkin
					end
				end
			end
			return oldNamecall(self, ...)
		end)
		
		setreadonly(mt, true)
		
		Client.CurrentInventory = allSkins
		
		local TClone, CTClone = LocalPlayer.SkinFolder.TFolder:Clone(), game.Players.LocalPlayer.SkinFolder.CTFolder:Clone()
		LocalPlayer.SkinFolder.TFolder:Destroy()
		LocalPlayer.SkinFolder.CTFolder:Destroy()
		TClone.Parent = LocalPlayer.SkinFolder
		CTClone.Parent = LocalPlayer.SkinFolder
				
	
	else
		
	end
end

button.Activated:Connect(onButtonActivated)
end))
ImageButton368.Name = "AntiSpec"
ImageButton368.Parent = Frame324
ImageButton368.Position = UDim2.new(0.0920000002, 0, 0.332215935, 0)
ImageButton368.Size = UDim2.new(0, 12, 0, 12)
ImageButton368.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton368.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton368.BorderColor = BrickColor.new("Really black")
ImageButton368.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton368.ZIndex = 2
ImageButton368.Image = "rbxassetid://5761429802"
ImageButton368.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton368.ImageTransparency = 0.25
TextLabel369.Name = "Antispec"
TextLabel369.Parent = ImageButton368
TextLabel369.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel369.Size = UDim2.new(0, 324, 0, 20)
TextLabel369.BackgroundColor = BrickColor.new("Institutional white")
TextLabel369.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel369.BackgroundTransparency = 1
TextLabel369.Font = Enum.Font.SourceSans
TextLabel369.FontSize = Enum.FontSize.Size28
TextLabel369.Text = "Anti spectator"
TextLabel369.TextColor = BrickColor.new("Institutional white")
TextLabel369.TextColor3 = Color3.new(1, 1, 1)
TextLabel369.TextSize = 26
TextLabel369.TextWrap = true
TextLabel369.TextWrapped = true
TextLabel369.TextXAlignment = Enum.TextXAlignment.Left
LocalScript370.Name = "13"
LocalScript370.Parent = ImageButton368
table.insert(cors,sandbox(LocalScript370,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)


	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		
	end
end
button.Activated:Connect(onButtonActivated)




end))
Frame371.Name = "Background"
Frame371.Parent = Frame324
Frame371.Position = UDim2.new(0.549000025, -150, 0.0549999997, 0)
Frame371.Size = UDim2.new(0, 259, 0, 27)
Frame371.BackgroundColor = BrickColor.new("Really black")
Frame371.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame371.BorderSizePixel = 0
Frame372.Name = "Bar"
Frame372.Parent = Frame371
Frame372.Position = UDim2.new(0, 0, 0.296296299, 0)
Frame372.Size = UDim2.new(0, 255, 0, 10)
Frame372.BackgroundColor = BrickColor.new("Dark taupe")
Frame372.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
Frame372.BorderSizePixel = 0
TextButton373.Name = "Button"
TextButton373.Parent = Frame372
TextButton373.Position = UDim2.new(0, 0, 0, -10)
TextButton373.Size = UDim2.new(0, 30, 0, 30)
TextButton373.BackgroundColor = BrickColor.new("Institutional white")
TextButton373.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton373.BorderSizePixel = 0
TextButton373.Draggable = true
TextButton373.Style = Enum.ButtonStyle.RobloxRoundButton
TextButton373.Font = Enum.Font.SourceSans
TextButton373.FontSize = Enum.FontSize.Size14
TextButton373.Text = ""
TextButton373.TextSize = 14
LocalScript374.Name = "Slider"
LocalScript374.Parent = TextButton373
table.insert(cors,sandbox(LocalScript374,function()

local sp = script.Parent
local bar = sp.Parent
local percent = sp.Parent.Parent.Percent
local run = game:GetService("RunService")

-- get original position
local xpos = {sp.Position.X.Scale, sp.Position.X.Offset}
local ypos = {sp.Position.Y.Scale, sp.Position.Y.Offset}

run.RenderStepped:connect(function()
	sp.Position = UDim2.new(sp.Position.X.Scale, sp.Position.X.Offset , ypos[1], ypos[2])
	if sp.Position.X.Offset >= bar.Size.X.Offset - sp.Size.X.Offset then -- triggered when the button goes over the bar's size
		sp.Position = UDim2.new(sp.Position.X.Scale, (bar.Size.X.Offset - sp.Size.X.Offset) , ypos[1], ypos[2])
	elseif sp.Position.X.Offset <= 0 then -- triggered when the button's position goes negative
		sp.Position = UDim2.new(xpos[1], xpos[2] , ypos[1], ypos[2])
	end

	percent.Value = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100)
	sp.ValueText.Text = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100) + 20
	
end)

end))
TextLabel375.Name = "ValueText"
TextLabel375.Parent = TextButton373
TextLabel375.Position = UDim2.new(-2, 0, 0.787, 0)
TextLabel375.Size = UDim2.new(0, 30, 0, 37)
TextLabel375.BackgroundColor = BrickColor.new("Institutional white")
TextLabel375.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel375.BackgroundTransparency = 1
TextLabel375.Font = Enum.Font.SourceSans
TextLabel375.FontSize = Enum.FontSize.Size24
TextLabel375.Text = "20"
TextLabel375.TextColor = BrickColor.new("Institutional white")
TextLabel375.TextColor3 = Color3.new(1, 1, 1)
TextLabel375.TextSize = 24
NumberValue376.Name = "Percent"
NumberValue376.Parent = Frame371
ImageButton377.Name = "Icon"
ImageButton377.Parent = Frame304
ImageButton377.Position = UDim2.new(0.179000005, 0, 0.0673290864, 0)
ImageButton377.Size = UDim2.new(0, 105, 0, 124)
ImageButton377.BackgroundColor = BrickColor.new("Really black")
ImageButton377.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton377.BackgroundTransparency = 1
ImageButton377.BorderColor = BrickColor.new("Really black")
ImageButton377.BorderColor3 = Color3.new(0, 0, 0)
ImageButton377.ZIndex = 100
ImageButton377.Image = "rbxassetid://5752445512"
ImageButton377.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton377.ScaleType = Enum.ScaleType.Fit
Frame378.Name = "Other border"
Frame378.Parent = Frame304
Frame378.Position = UDim2.new(0, 0, 0, -3)
Frame378.Visible = false
Frame378.Size = UDim2.new(0, 166, 0, 3)
Frame378.BackgroundColor = BrickColor.new("Dirt brown")
Frame378.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame378.BorderSizePixel = 0
Frame378.ZIndex = 3
Frame379.Name = "Side Border"
Frame379.Parent = Frame304
Frame379.Position = UDim2.new(1, 0, -0.0152441747, 0)
Frame379.Size = UDim2.new(0, 3, 0, 146)
Frame379.BackgroundColor = BrickColor.new("Dirt brown")
Frame379.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame379.BorderSizePixel = 0
Frame379.ZIndex = 2
Frame380.Name = "AA"
Frame380.Parent = Frame18
Frame380.Position = UDim2.new(0, 0, 0.142078012, 0)
Frame380.Size = UDim2.new(0, 163, 0, 142)
Frame380.BackgroundColor = BrickColor.new("Really black")
Frame380.BackgroundColor3 = Color3.new(0, 0, 0)
Frame380.BorderColor = BrickColor.new("Really black")
Frame380.BorderColor3 = Color3.new(0, 0, 0)
Frame380.BorderSizePixel = 0
LocalScript381.Name = "Selected"
LocalScript381.Parent = Frame380
table.insert(cors,sandbox(LocalScript381,function()
local button = script.Parent.Icon


local function onMouseEntered()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.Icon.ImageColor3 ~= Color3.new(1, 1, 1)then
				script.Parent.Icon.ImageColor3 = Color3.new(1, 1, 1)
			end
		end
		button.Activated:Connect(onButtonActivated)
	end
	
end
local function onMouseLeft()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end

     
	
button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton382.Name = "Icon"
ImageButton382.Parent = Frame380
ImageButton382.Position = UDim2.new(0, 11, 0, 4)
ImageButton382.Size = UDim2.new(0, 140, 0, 140)
ImageButton382.BackgroundColor = BrickColor.new("Really black")
ImageButton382.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton382.BackgroundTransparency = 1
ImageButton382.BorderColor = BrickColor.new("Really black")
ImageButton382.BorderColor3 = Color3.new(0, 0, 0)
ImageButton382.BorderSizePixel = 0
ImageButton382.ZIndex = 100
ImageButton382.Image = "rbxassetid://5750421435"
ImageButton382.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton382.ScaleType = Enum.ScaleType.Fit
Frame383.Name = "Side Border"
Frame383.Parent = Frame380
Frame383.Position = UDim2.new(1, 0, -0.0158579648, 0)
Frame383.Size = UDim2.new(0, 3, 0, 147)
Frame383.BackgroundColor = BrickColor.new("Dirt brown")
Frame383.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame383.BorderSizePixel = 0
Frame383.ZIndex = 2
Frame384.Name = "Other border"
Frame384.Parent = Frame380
Frame384.Position = UDim2.new(0, 0, 0, -3)
Frame384.Visible = false
Frame384.Size = UDim2.new(0, 166, 0, 3)
Frame384.BackgroundColor = BrickColor.new("Dirt brown")
Frame384.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame384.BorderSizePixel = 0
Frame384.ZIndex = 3
Frame385.Name = "Main"
Frame385.Parent = Frame380
Frame385.Position = UDim2.new(1.12899995, 0, -0.924000025, 0)
Frame385.Visible = false
Frame385.Size = UDim2.new(0, 941, 0, 993)
Frame385.BackgroundColor = BrickColor.new("Cyan")
Frame385.BackgroundColor3 = Color3.new(0, 0.701961, 1)
Frame385.BackgroundTransparency = 1
Frame385.BorderSizePixel = 0
Frame386.Name = "FakeLagTab"
Frame386.Parent = Frame385
Frame386.Position = UDim2.new(0.526000082, 0, 0.0320000015, 0)
Frame386.Size = UDim2.new(0, 424, 0, 624)
Frame386.BackgroundColor = BrickColor.new("Really black")
Frame386.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame386.BorderColor = BrickColor.new("Dirt brown")
Frame386.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame386.BorderSizePixel = 2
ImageButton387.Name = "Fakelag"
ImageButton387.Parent = Frame386
ImageButton387.Position = UDim2.new(0.0909999982, 0, 0.0500256419, 0)
ImageButton387.Size = UDim2.new(0, 12, 0, 12)
ImageButton387.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton387.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton387.BorderColor = BrickColor.new("Really black")
ImageButton387.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton387.ZIndex = 999
ImageButton387.Image = "rbxassetid://5761429802"
ImageButton387.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton387.ImageTransparency = 0.25
LocalScript388.Name = "FakeLag"
LocalScript388.Parent = ImageButton387
table.insert(cors,sandbox(LocalScript388,function()
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local body = plr.Character
local player = game.Players.LocalPlayer
local chokelevel = tonumber(script.Parent.Parent.Background.Bar.Button.ValueText.Text)

function packetchoke(amount)
	local netSettings = settings():GetService('NetworkSettings')
	netSettings.IncomingReplicationLag = amount
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.tags.Fakelag.Visible = true	
end
	
function stoppacketchoke()
	local netSettings = settings():GetService('NetworkSettings')
	netSettings.IncomingReplicationLag = 0
	script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.tags.Fakelag.Visible = false
end

repeat wait() until script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42)
if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
	while wait() do
		if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then					
			packetchoke(chokelevel)
			if script.Parent.Parent.Frequency.Selection.Text == "Low" then
				wait(0.1)
				stoppacketchoke()
				wait(0.5)
			end
			
			if script.Parent.Parent.Frequency.Selection.Text == "Medium" then
				wait(0.25)
				stoppacketchoke()
				wait(1)
			end
			if script.Parent.Parent.Frequency.Selection.Text == "High" then
				wait(0.5)
				stoppacketchoke()
				wait(2)
			end
		end
	end
end





end))
LocalScript389.Name = "Toggle"
LocalScript389.Parent = ImageButton387
table.insert(cors,sandbox(LocalScript389,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)

	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)

	end
end
button.Activated:Connect(onButtonActivated)




end))
TextLabel390.Name = "Fakelag"
TextLabel390.Parent = ImageButton387
TextLabel390.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel390.Size = UDim2.new(0, 324, 0, 20)
TextLabel390.BackgroundColor = BrickColor.new("Institutional white")
TextLabel390.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel390.BackgroundTransparency = 1
TextLabel390.Font = Enum.Font.SourceSans
TextLabel390.FontSize = Enum.FontSize.Size28
TextLabel390.Text = "Fake lag"
TextLabel390.TextColor = BrickColor.new("Institutional white")
TextLabel390.TextColor3 = Color3.new(1, 1, 1)
TextLabel390.TextSize = 26
TextLabel390.TextWrap = true
TextLabel390.TextWrapped = true
TextLabel390.TextXAlignment = Enum.TextXAlignment.Left
TextLabel391.Name = "Fake lag"
TextLabel391.Parent = Frame386
TextLabel391.Position = UDim2.new(0.0361394361, 0, -0.00979359541, 0)
TextLabel391.Size = UDim2.new(0, 97, 0, 10)
TextLabel391.Active = true
TextLabel391.BackgroundColor = BrickColor.new("Really black")
TextLabel391.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel391.BorderColor = BrickColor.new("Really black")
TextLabel391.BorderColor3 = Color3.new(0, 0, 0)
TextLabel391.BorderSizePixel = 0
TextLabel391.ZIndex = 2
TextLabel391.Font = Enum.Font.SourceSansBold
TextLabel391.FontSize = Enum.FontSize.Size28
TextLabel391.Text = "Fake lag"
TextLabel391.TextColor = BrickColor.new("Mid gray")
TextLabel391.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel391.TextSize = 28
TextLabel391.TextWrap = true
TextLabel391.TextWrapped = true
ImageButton392.Name = "FrequencyTag"
ImageButton392.Parent = Frame386
ImageButton392.Position = UDim2.new(0.0909999982, 0, 0.102051288, 0)
ImageButton392.Size = UDim2.new(0, 12, 0, 12)
ImageButton392.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton392.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton392.BackgroundTransparency = 1
ImageButton392.BorderColor = BrickColor.new("Really black")
ImageButton392.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton392.ZIndex = 999
ImageButton392.Image = "rbxassetid://5761429802"
ImageButton392.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton392.ImageTransparency = 1
TextLabel393.Name = "Frequency"
TextLabel393.Parent = ImageButton392
TextLabel393.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel393.Size = UDim2.new(0, 324, 0, 20)
TextLabel393.BackgroundColor = BrickColor.new("Institutional white")
TextLabel393.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel393.BackgroundTransparency = 1
TextLabel393.Font = Enum.Font.SourceSans
TextLabel393.FontSize = Enum.FontSize.Size28
TextLabel393.Text = "Delay"
TextLabel393.TextColor = BrickColor.new("Institutional white")
TextLabel393.TextColor3 = Color3.new(1, 1, 1)
TextLabel393.TextSize = 26
TextLabel393.TextWrap = true
TextLabel393.TextWrapped = true
TextLabel393.TextXAlignment = Enum.TextXAlignment.Left
Frame394.Name = "Frequency"
Frame394.Parent = Frame386
Frame394.Position = UDim2.new(0.194999993, 0, 0.294, 0)
Frame394.Size = UDim2.new(0.612999976, 0, 0.0209999997, 0)
Frame394.BackgroundColor = BrickColor.new("Really black")
Frame394.BackgroundColor3 = Color3.new(0, 0, 0)
Frame394.BackgroundTransparency = 1
Frame394.BorderSizePixel = 0
Frame394.ZIndex = 3
TextButton395.Name = "Selection"
TextButton395.Parent = Frame394
TextButton395.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton395.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton395.BackgroundColor = BrickColor.new("Black")
TextButton395.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton395.BorderColor = BrickColor.new("Dirt brown")
TextButton395.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton395.BorderSizePixel = 3
TextButton395.Font = Enum.Font.SourceSans
TextButton395.FontSize = Enum.FontSize.Size28
TextButton395.Text = "[...]"
TextButton395.TextColor = BrickColor.new("Institutional white")
TextButton395.TextColor3 = Color3.new(1, 1, 1)
TextButton395.TextSize = 26
TextButton395.TextWrap = true
TextButton395.TextWrapped = true
Frame396.Name = "Menu"
Frame396.Parent = Frame394
Frame396.Position = UDim2.new(0, 0, -5.02099895, 3)
Frame396.Visible = false
Frame396.Size = UDim2.new(1, 0, 6.33255768, 0)
Frame396.BackgroundColor = BrickColor.new("Black")
Frame396.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame396.BorderColor = BrickColor.new("Dirt brown")
Frame396.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame396.BorderSizePixel = 3
Frame396.ZIndex = 4
TextButton397.Name = "Button"
TextButton397.Parent = Frame396
TextButton397.Position = UDim2.new(0.00247294386, 0, 0.0324343704, 0)
TextButton397.Size = UDim2.new(0.99368149, 0, -0.0368355587, 35)
TextButton397.BackgroundColor = BrickColor.new("Black metallic")
TextButton397.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton397.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton397.BorderSizePixel = 0
TextButton397.ZIndex = 4
TextButton397.Font = Enum.Font.SourceSans
TextButton397.FontSize = Enum.FontSize.Size28
TextButton397.Text = "Low"
TextButton397.TextColor = BrickColor.new("Institutional white")
TextButton397.TextColor3 = Color3.new(1, 1, 1)
TextButton397.TextSize = 26
TextButton397.TextWrap = true
TextButton397.TextWrapped = true
TextButton398.Name = "Button2"
TextButton398.Parent = Frame396
TextButton398.Position = UDim2.new(0.00247294386, 0, 0.373999953, 0)
TextButton398.Size = UDim2.new(0.99752754, 0, -0.0601450615, 35)
TextButton398.BackgroundColor = BrickColor.new("Black metallic")
TextButton398.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton398.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton398.BorderSizePixel = 0
TextButton398.ZIndex = 4
TextButton398.Font = Enum.Font.SourceSans
TextButton398.FontSize = Enum.FontSize.Size28
TextButton398.Text = "Medium"
TextButton398.TextColor = BrickColor.new("Institutional white")
TextButton398.TextColor3 = Color3.new(1, 1, 1)
TextButton398.TextSize = 26
TextButton398.TextWrap = true
TextButton398.TextWrapped = true
TextButton399.Name = "Button3"
TextButton399.Parent = Frame396
TextButton399.Position = UDim2.new(0, 0, 0.692255855, 0)
TextButton399.Size = UDim2.new(1, 0, -0.0738480985, 35)
TextButton399.BackgroundColor = BrickColor.new("Black metallic")
TextButton399.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton399.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton399.BorderSizePixel = 0
TextButton399.ZIndex = 4
TextButton399.Font = Enum.Font.SourceSans
TextButton399.FontSize = Enum.FontSize.Size28
TextButton399.Text = "High"
TextButton399.TextColor = BrickColor.new("Institutional white")
TextButton399.TextColor3 = Color3.new(1, 1, 1)
TextButton399.TextSize = 26
TextButton399.TextWrap = true
TextButton399.TextWrapped = true
LocalScript400.Name = "Effect"
LocalScript400.Parent = Frame394
table.insert(cors,sandbox(LocalScript400,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
Frame401.Name = "Background"
Frame401.Parent = Frame386
Frame401.Position = UDim2.new(0.546641529, -150, 0.256923079, 0)
Frame401.Size = UDim2.new(0, 259, 0, 27)
Frame401.BackgroundColor = BrickColor.new("Really black")
Frame401.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame401.BorderSizePixel = 0
Frame402.Name = "Bar"
Frame402.Parent = Frame401
Frame402.Position = UDim2.new(0, 0, 0.296296299, 0)
Frame402.Size = UDim2.new(0, 255, 0, 10)
Frame402.BackgroundColor = BrickColor.new("Dark taupe")
Frame402.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
Frame402.BorderSizePixel = 0
TextButton403.Name = "Button"
TextButton403.Parent = Frame402
TextButton403.Position = UDim2.new(0, 0, 0, -10)
TextButton403.Size = UDim2.new(0, 30, 0, 30)
TextButton403.BackgroundColor = BrickColor.new("Institutional white")
TextButton403.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton403.BorderSizePixel = 0
TextButton403.Draggable = true
TextButton403.Style = Enum.ButtonStyle.RobloxRoundButton
TextButton403.Font = Enum.Font.SourceSans
TextButton403.FontSize = Enum.FontSize.Size14
TextButton403.Text = ""
TextButton403.TextSize = 14
LocalScript404.Name = "Slider"
LocalScript404.Parent = TextButton403
table.insert(cors,sandbox(LocalScript404,function()

local sp = script.Parent
local bar = sp.Parent
local percent = sp.Parent.Parent.Percent
local run = game:GetService("RunService")

-- get original position
local xpos = {sp.Position.X.Scale, sp.Position.X.Offset}
local ypos = {sp.Position.Y.Scale, sp.Position.Y.Offset}

run.RenderStepped:connect(function()
	sp.Position = UDim2.new(sp.Position.X.Scale, sp.Position.X.Offset , ypos[1], ypos[2])
	if sp.Position.X.Offset >= bar.Size.X.Offset - sp.Size.X.Offset then -- triggered when the button goes over the bar's size
		sp.Position = UDim2.new(sp.Position.X.Scale, (bar.Size.X.Offset - sp.Size.X.Offset) , ypos[1], ypos[2])
	elseif sp.Position.X.Offset <= 0 then -- triggered when the button's position goes negative
		sp.Position = UDim2.new(xpos[1], xpos[2] , ypos[1], ypos[2])
	end

	percent.Value = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100)
	sp.ValueText.Text = math.floor((sp.Position.X.Offset / (bar.Size.X.Offset - sp.Size.X.Offset)) * 100)
	
end)

end))
TextLabel405.Name = "ValueText"
TextLabel405.Parent = TextButton403
TextLabel405.Position = UDim2.new(-2, 0, 0.787, 0)
TextLabel405.Size = UDim2.new(0, 30, 0, 37)
TextLabel405.BackgroundColor = BrickColor.new("Institutional white")
TextLabel405.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel405.BackgroundTransparency = 1
TextLabel405.Font = Enum.Font.SourceSans
TextLabel405.FontSize = Enum.FontSize.Size24
TextLabel405.Text = "0"
TextLabel405.TextColor = BrickColor.new("Institutional white")
TextLabel405.TextColor3 = Color3.new(1, 1, 1)
TextLabel405.TextSize = 24
NumberValue406.Name = "Percent"
NumberValue406.Parent = Frame401
ImageButton407.Name = "AmountTag"
ImageButton407.Parent = Frame386
ImageButton407.Position = UDim2.new(0.0909999982, 0, 0.102051288, 0)
ImageButton407.Size = UDim2.new(0, 12, 0, 12)
ImageButton407.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton407.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton407.BackgroundTransparency = 1
ImageButton407.BorderColor = BrickColor.new("Really black")
ImageButton407.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton407.ZIndex = 999
ImageButton407.Image = "rbxassetid://5761429802"
ImageButton407.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton407.ImageTransparency = 1
TextLabel408.Name = "Amount"
TextLabel408.Parent = ImageButton407
TextLabel408.Position = UDim2.new(3.6559999, 0, 5.91666651, -6)
TextLabel408.Size = UDim2.new(0, 324, 0, 20)
TextLabel408.BackgroundColor = BrickColor.new("Institutional white")
TextLabel408.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel408.BackgroundTransparency = 1
TextLabel408.Font = Enum.Font.SourceSans
TextLabel408.FontSize = Enum.FontSize.Size28
TextLabel408.Text = "Amount"
TextLabel408.TextColor = BrickColor.new("Institutional white")
TextLabel408.TextColor3 = Color3.new(1, 1, 1)
TextLabel408.TextSize = 26
TextLabel408.TextWrap = true
TextLabel408.TextWrapped = true
TextLabel408.TextXAlignment = Enum.TextXAlignment.Left
Frame409.Name = "AntiAimTab"
Frame409.Parent = Frame385
Frame409.Position = UDim2.new(0.0236982461, 0, 0.0315125808, 0)
Frame409.Size = UDim2.new(0, 424, 0, 954)
Frame409.BackgroundColor = BrickColor.new("Really black")
Frame409.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame409.BorderColor = BrickColor.new("Dirt brown")
Frame409.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame409.BorderSizePixel = 2
Frame410.Name = "Yaw"
Frame410.Parent = Frame409
Frame410.Position = UDim2.new(0.194999993, 0, 0.271327049, 0)
Frame410.Size = UDim2.new(0.61330384, 0, 0.0147641124, 0)
Frame410.BackgroundColor = BrickColor.new("Really black")
Frame410.BackgroundColor3 = Color3.new(0, 0, 0)
Frame410.BackgroundTransparency = 1
Frame410.BorderSizePixel = 0
Frame410.ZIndex = 3
TextButton411.Name = "Selection"
TextButton411.Parent = Frame410
TextButton411.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton411.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton411.BackgroundColor = BrickColor.new("Black")
TextButton411.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton411.BorderColor = BrickColor.new("Dirt brown")
TextButton411.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton411.BorderSizePixel = 3
TextButton411.Font = Enum.Font.SourceSans
TextButton411.FontSize = Enum.FontSize.Size28
TextButton411.Text = "[...]"
TextButton411.TextColor = BrickColor.new("Institutional white")
TextButton411.TextColor3 = Color3.new(1, 1, 1)
TextButton411.TextSize = 26
TextButton411.TextWrap = true
TextButton411.TextWrapped = true
Frame412.Name = "Menu"
Frame412.Parent = Frame410
Frame412.Position = UDim2.new(0, 0, -5.02099895, 3)
Frame412.Visible = false
Frame412.Size = UDim2.new(1, 0, 14.5319309, 0)
Frame412.BackgroundColor = BrickColor.new("Black")
Frame412.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame412.BorderColor = BrickColor.new("Dirt brown")
Frame412.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame412.BorderSizePixel = 3
Frame412.ZIndex = 4
TextButton413.Name = "Button5"
TextButton413.Parent = Frame412
TextButton413.Position = UDim2.new(0, 0, -0.00125242095, 0)
TextButton413.Size = UDim2.new(1, 0, -0.0248066951, 35)
TextButton413.BackgroundColor = BrickColor.new("Black metallic")
TextButton413.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton413.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton413.BorderSizePixel = 0
TextButton413.ZIndex = 4
TextButton413.Font = Enum.Font.SourceSans
TextButton413.FontSize = Enum.FontSize.Size28
TextButton413.Text = "Static"
TextButton413.TextColor = BrickColor.new("Institutional white")
TextButton413.TextColor3 = Color3.new(1, 1, 1)
TextButton413.TextSize = 26
TextButton413.TextWrap = true
TextButton413.TextWrapped = true
TextButton414.Name = "Button4"
TextButton414.Parent = Frame412
TextButton414.Position = UDim2.new(0, 0, 0.286888033, 0)
TextButton414.Size = UDim2.new(1, 0, -0.0248066951, 35)
TextButton414.BackgroundColor = BrickColor.new("Black metallic")
TextButton414.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton414.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton414.BorderSizePixel = 0
TextButton414.ZIndex = 4
TextButton414.Font = Enum.Font.SourceSans
TextButton414.FontSize = Enum.FontSize.Size28
TextButton414.Text = "Backwards"
TextButton414.TextColor = BrickColor.new("Institutional white")
TextButton414.TextColor3 = Color3.new(1, 1, 1)
TextButton414.TextSize = 26
TextButton414.TextWrap = true
TextButton414.TextWrapped = true
TextButton415.Name = "Button"
TextButton415.Parent = Frame412
TextButton415.Position = UDim2.new(0, 0, 0.14072068, 0)
TextButton415.Size = UDim2.new(1, 0, -0.0248066951, 35)
TextButton415.BackgroundColor = BrickColor.new("Black metallic")
TextButton415.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton415.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton415.BorderSizePixel = 0
TextButton415.ZIndex = 4
TextButton415.Font = Enum.Font.SourceSans
TextButton415.FontSize = Enum.FontSize.Size28
TextButton415.Text = "Forwards"
TextButton415.TextColor = BrickColor.new("Institutional white")
TextButton415.TextColor3 = Color3.new(1, 1, 1)
TextButton415.TextSize = 26
TextButton415.TextWrap = true
TextButton415.TextWrapped = true
TextButton416.Name = "Button2"
TextButton416.Parent = Frame412
TextButton416.Position = UDim2.new(0, 0, 0.572992861, 0)
TextButton416.Size = UDim2.new(1, 0, -0.0248066951, 35)
TextButton416.BackgroundColor = BrickColor.new("Black metallic")
TextButton416.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton416.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton416.BorderSizePixel = 0
TextButton416.ZIndex = 4
TextButton416.Font = Enum.Font.SourceSans
TextButton416.FontSize = Enum.FontSize.Size28
TextButton416.Text = "Jitter left"
TextButton416.TextColor = BrickColor.new("Institutional white")
TextButton416.TextColor3 = Color3.new(1, 1, 1)
TextButton416.TextSize = 26
TextButton416.TextWrap = true
TextButton416.TextWrapped = true
TextButton417.Name = "Button6"
TextButton417.Parent = Frame412
TextButton417.Position = UDim2.new(0, 0, 0.429973274, 0)
TextButton417.Size = UDim2.new(1, 0, -0.0248066951, 35)
TextButton417.BackgroundColor = BrickColor.new("Black metallic")
TextButton417.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton417.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton417.BorderSizePixel = 0
TextButton417.ZIndex = 4
TextButton417.Font = Enum.Font.SourceSans
TextButton417.FontSize = Enum.FontSize.Size28
TextButton417.Text = "Spin"
TextButton417.TextColor = BrickColor.new("Institutional white")
TextButton417.TextColor3 = Color3.new(1, 1, 1)
TextButton417.TextSize = 26
TextButton417.TextWrap = true
TextButton417.TextWrapped = true
TextButton418.Name = "Button3"
TextButton418.Parent = Frame412
TextButton418.Position = UDim2.new(0, 0, 0.7134009, 0)
TextButton418.Size = UDim2.new(1, 0, -0.0248066951, 35)
TextButton418.BackgroundColor = BrickColor.new("Black metallic")
TextButton418.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton418.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton418.BorderSizePixel = 0
TextButton418.ZIndex = 4
TextButton418.Font = Enum.Font.SourceSans
TextButton418.FontSize = Enum.FontSize.Size28
TextButton418.Text = "Jitter right"
TextButton418.TextColor = BrickColor.new("Institutional white")
TextButton418.TextColor3 = Color3.new(1, 1, 1)
TextButton418.TextSize = 26
TextButton418.TextWrap = true
TextButton418.TextWrapped = true
TextButton419.Name = "Button7"
TextButton419.Parent = Frame412
TextButton419.Position = UDim2.new(0, 0, 0.853809237, 0)
TextButton419.Size = UDim2.new(1, 0, -0.0248066951, 35)
TextButton419.BackgroundColor = BrickColor.new("Black metallic")
TextButton419.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton419.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton419.BorderSizePixel = 0
TextButton419.ZIndex = 4
TextButton419.Font = Enum.Font.SourceSans
TextButton419.FontSize = Enum.FontSize.Size28
TextButton419.Text = "Jitter random"
TextButton419.TextColor = BrickColor.new("Institutional white")
TextButton419.TextColor3 = Color3.new(1, 1, 1)
TextButton419.TextSize = 26
TextButton419.TextWrap = true
TextButton419.TextWrapped = true
LocalScript420.Name = "Effect"
LocalScript420.Parent = Frame410
table.insert(cors,sandbox(LocalScript420,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
ImageButton421.Name = "PitchTag"
ImageButton421.Parent = Frame409
ImageButton421.Position = UDim2.new(0.0909999982, 0, 0.0700000003, 0)
ImageButton421.Size = UDim2.new(0, 12, 0, 12)
ImageButton421.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton421.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton421.BackgroundTransparency = 1
ImageButton421.BorderColor = BrickColor.new("Really black")
ImageButton421.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton421.ZIndex = 999
ImageButton421.Image = "rbxassetid://5761429802"
ImageButton421.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton421.ImageTransparency = 1
TextLabel422.Name = "Pitch"
TextLabel422.Parent = ImageButton421
TextLabel422.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel422.Size = UDim2.new(0, 324, 0, 20)
TextLabel422.BackgroundColor = BrickColor.new("Institutional white")
TextLabel422.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel422.BackgroundTransparency = 1
TextLabel422.Font = Enum.Font.SourceSans
TextLabel422.FontSize = Enum.FontSize.Size28
TextLabel422.Text = "Pitch"
TextLabel422.TextColor = BrickColor.new("Institutional white")
TextLabel422.TextColor3 = Color3.new(1, 1, 1)
TextLabel422.TextSize = 26
TextLabel422.TextWrap = true
TextLabel422.TextWrapped = true
TextLabel422.TextXAlignment = Enum.TextXAlignment.Left
ImageButton423.Name = "YawTag"
ImageButton423.Parent = Frame409
ImageButton423.Position = UDim2.new(0.0909999982, 0, 0.14232704, 0)
ImageButton423.Size = UDim2.new(0, 12, 0, 12)
ImageButton423.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton423.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton423.BackgroundTransparency = 1
ImageButton423.BorderColor = BrickColor.new("Really black")
ImageButton423.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton423.ZIndex = 999
ImageButton423.Image = "rbxassetid://5761429802"
ImageButton423.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton423.ImageTransparency = 1
TextLabel424.Name = "Yaw"
TextLabel424.Parent = ImageButton423
TextLabel424.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel424.Size = UDim2.new(0, 324, 0, 20)
TextLabel424.BackgroundColor = BrickColor.new("Institutional white")
TextLabel424.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel424.BackgroundTransparency = 1
TextLabel424.Font = Enum.Font.SourceSans
TextLabel424.FontSize = Enum.FontSize.Size28
TextLabel424.Text = "Yaw"
TextLabel424.TextColor = BrickColor.new("Institutional white")
TextLabel424.TextColor3 = Color3.new(1, 1, 1)
TextLabel424.TextSize = 26
TextLabel424.TextWrap = true
TextLabel424.TextWrapped = true
TextLabel424.TextXAlignment = Enum.TextXAlignment.Left
ImageButton425.Name = "AA"
ImageButton425.Parent = Frame409
ImageButton425.Position = UDim2.new(0.0909999982, 0, 0.0340000018, 0)
ImageButton425.Size = UDim2.new(0, 12, 0, 12)
ImageButton425.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton425.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton425.BorderColor = BrickColor.new("Really black")
ImageButton425.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton425.ZIndex = 999
ImageButton425.Image = "rbxassetid://5761429802"
ImageButton425.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton425.ImageTransparency = 0.25
LocalScript426.Name = "Toggle"
LocalScript426.Parent = ImageButton425
table.insert(cors,sandbox(LocalScript426,function()
local button = script.Parent

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)

	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)

	end
end
button.Activated:Connect(onButtonActivated)




end))
LocalScript427.Name = "YAW"
LocalScript427.Parent = ImageButton425
table.insert(cors,sandbox(LocalScript427,function()
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local cam = workspace.CurrentCamera

--Old
function characterrotate(pos)
	pcall(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
			if game.Players.LocalPlayer.Character then
				game.Players.LocalPlayer.Character.Humanoid.AutoRotate = false
				local gyro = Instance.new('BodyGyro')
				gyro.D = 0
				gyro.P = 1000000
				gyro.MaxTorque = Vector3.new(0, 1000000, 0)
				gyro.Parent = game.Players.LocalPlayer.Character.UpperTorso
				gyro.CFrame = CFrame.new(gyro.Parent.Position,  pos)
				wait()
				gyro:Destroy()
			end
		end
	end)
end
local backrotation = CFrame.new(-4,0,0)

function AA(angle)
	plr.Character.HumanoidRootPart.CFrame = CFrame.new(plr.Character.HumanoidRootPart.Position, plr.Character.HumanoidRootPart.Position + Vector3.new(cam.CFrame.lookVector.X, 0, cam.CFrame.lookVector.Z)) * CFrame.Angles(0, math.rad(angle), 0)
end

function wait1(seconds)
	wait(seconds)
end

function Left()
	if not wait1() then
		local spin = Instance.new('BodyAngularVelocity',game.Players.LocalPlayer.Character:FindFirstChild('HumanoidRootPart'))
		spin.AngularVelocity = Vector3.new(0, 69000, 0)
		spin.MaxTorque = Vector3.new(0, 15000, 0)
		wait1(0.05)
		spin:Destroy()
	end
end

function Right()
	if not wait1() then
		local spin = Instance.new('BodyAngularVelocity',game.Players.LocalPlayer.Character:FindFirstChild('HumanoidRootPart'))
		spin.AngularVelocity = Vector3.new(0, -69000, 0)
		spin.MaxTorque = Vector3.new(0, 15000, 0)
		wait1(0.05)
		spin:Destroy()
	end
end

--[[
pcall(function()
	repeat wait() until script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42)
	if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
		game['Run Service'].Stepped:connect(function()
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Forward" then					
				game.Players.LocalPlayer.Character.Humanoid.AutoRotate = true
			end

			while script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Jitter right" do
				while game.Players.LocalPlayer.Character do
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					while game.Players.LocalPlayer.Character do
						characterrotate((workspace.CurrentCamera.CFrame * backrotation).p)
						Right()
					end
				end
			end
			
			while script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Jitter left" do
				while game.Players.LocalPlayer.Character do
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					while game.Players.LocalPlayer.Character do
						characterrotate((workspace.CurrentCamera.CFrame * backrotation).p)
						Left()
					end
				end
			end
			
			while script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Jitter random" do
				while game.Players.LocalPlayer.Character do
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					while game.Players.LocalPlayer.Character do
						Left()
						Right()
					end
				end
			end
			
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Spin" then
				if game.Players.LocalPlayer.Character then
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					if game.Players.LocalPlayer.Character then
						game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
						local spin = Instance.new('BodyAngularVelocity',game.Players.LocalPlayer.Character:FindFirstChild('HumanoidRootPart'))
						spin.AngularVelocity = Vector3.new(0, 90000, 0)
						spin.MaxTorque = Vector3.new(0, 15000, 0)
						wait()
						spin:Destroy()
					end
				end
			end

			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Backwards" then					
				characterrotate((workspace.CurrentCamera.CFrame * backrotation).p)
			end

			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Static" then					
				game.Players.LocalPlayer.Character.Humanoid.AutoRotate = false
			end
		end)
	else
		game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = true			
	end	
end)
--]]


pcall(function()
	repeat wait() until script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42)
	if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
		game['Run Service'].RenderStepped:connect(function()
			while script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Forward" do					
				game.Players.LocalPlayer.Character.Humanoid.AutoRotate = true
			end

			while script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Jitter right" do
				while game.Players.LocalPlayer.Character do
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					while game.Players.LocalPlayer.Character do
						AA(math.random(90, 180))
						wait(1/20)
					end
				end
			end

			while script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Jitter left" do
				while game.Players.LocalPlayer.Character do
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					while game.Players.LocalPlayer.Character do
						AA(math.random(180, 270))
						wait(1/20)
					end
				end
			end

			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Jitter random" then
				if game.Players.LocalPlayer.Character then
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					if game.Players.LocalPlayer.Character then
						AA(math.random(110,250))
						wait(1/20)
					end
				end
			end

			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Spin" then
				if game.Players.LocalPlayer.Character then
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					if game.Players.LocalPlayer.Character then
						game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
						local spin = Instance.new('BodyAngularVelocity',game.Players.LocalPlayer.Character:FindFirstChild('HumanoidRootPart'))
						spin.AngularVelocity = Vector3.new(0, 90000, 0)
						spin.MaxTorque = Vector3.new(0, 35000, 0)
						wait()
						spin:Destroy()
					end
				end
			end

			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Backwards" then
				if game.Players.LocalPlayer.Character then
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
					if game.Players.LocalPlayer.Character then
						game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = false
						AA(180)
						wait(1/100)
					end
				end
			end

			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Static" then					
				game.Players.LocalPlayer.Character.Humanoid.AutoRotate = false
			end
		end)
	else
		game.Players.LocalPlayer.Character:WaitForChild("Humanoid").AutoRotate = true			
	end	
end)
end))
TextLabel428.Name = "AA"
TextLabel428.Parent = ImageButton425
TextLabel428.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel428.Size = UDim2.new(0, 324, 0, 20)
TextLabel428.BackgroundColor = BrickColor.new("Institutional white")
TextLabel428.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel428.BackgroundTransparency = 1
TextLabel428.Font = Enum.Font.SourceSans
TextLabel428.FontSize = Enum.FontSize.Size28
TextLabel428.Text = "Anti aimbot"
TextLabel428.TextColor = BrickColor.new("Institutional white")
TextLabel428.TextColor3 = Color3.new(1, 1, 1)
TextLabel428.TextSize = 26
TextLabel428.TextWrap = true
TextLabel428.TextWrapped = true
TextLabel428.TextXAlignment = Enum.TextXAlignment.Left
LocalScript429.Name = "PITCH"
LocalScript429.Parent = ImageButton425
table.insert(cors,sandbox(LocalScript429,function()
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local cam = workspace.CurrentCamera

pcall(function()
	repeat wait() until script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42)
	if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) then
		game['Run Service'].Stepped:connect(function()
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Pitch.Selection.Text == "Up" then
				if game.Players.LocalPlayer.Character then
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid")
					if game.Players.LocalPlayer.Character then
						game:GetService("ReplicatedStorage").Events.ControlTurn:FireServer("1.1")
					end
				end
			end
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Pitch.Selection.Text == "Down" then
				if game.Players.LocalPlayer.Character then
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid")
					if game.Players.LocalPlayer.Character then
						game:GetService("ReplicatedStorage").Events.ControlTurn:FireServer("-1.1")
					end
				end
			end
			if script.Parent.BackgroundColor3 == Color3.fromRGB(181, 255, 42) and script.Parent.Parent.Yaw.Selection.Text == "Zero" then
				if game.Players.LocalPlayer.Character then
					game.Players.LocalPlayer.Character:WaitForChild("Humanoid")
					if game.Players.LocalPlayer.Character then
						game:GetService("ReplicatedStorage").Events.ControlTurn:FireServer("0")
					end
				end
			end
		end)
	else
		
	end	
end)

			

end))
Frame430.Name = "Pitch"
Frame430.Parent = Frame409
Frame430.Position = UDim2.new(0.194999993, 0, 0.199000001, 0)
Frame430.Size = UDim2.new(0.61330384, 0, 0.0147641124, 0)
Frame430.BackgroundColor = BrickColor.new("Really black")
Frame430.BackgroundColor3 = Color3.new(0, 0, 0)
Frame430.BackgroundTransparency = 1
Frame430.BorderSizePixel = 0
Frame430.ZIndex = 3
TextButton431.Name = "Selection"
TextButton431.Parent = Frame430
TextButton431.Position = UDim2.new(0, 0, -6.90674925, 0)
TextButton431.Size = UDim2.new(1, 0, 2.01903486, 0)
TextButton431.BackgroundColor = BrickColor.new("Black")
TextButton431.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
TextButton431.BorderColor = BrickColor.new("Dirt brown")
TextButton431.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
TextButton431.BorderSizePixel = 3
TextButton431.Font = Enum.Font.SourceSans
TextButton431.FontSize = Enum.FontSize.Size28
TextButton431.Text = "[...]"
TextButton431.TextColor = BrickColor.new("Institutional white")
TextButton431.TextColor3 = Color3.new(1, 1, 1)
TextButton431.TextSize = 26
TextButton431.TextWrap = true
TextButton431.TextWrapped = true
Frame432.Name = "Menu"
Frame432.Parent = Frame430
Frame432.Position = UDim2.new(0, 0, -5.02099895, 3)
Frame432.Visible = false
Frame432.Size = UDim2.new(1, 0, 6.33255768, 0)
Frame432.BackgroundColor = BrickColor.new("Black")
Frame432.BackgroundColor3 = Color3.new(0.172549, 0.172549, 0.172549)
Frame432.BorderColor = BrickColor.new("Dirt brown")
Frame432.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame432.BorderSizePixel = 3
Frame432.ZIndex = 4
TextButton433.Name = "Button"
TextButton433.Parent = Frame432
TextButton433.Size = UDim2.new(1, 0, -0.0539217964, 35)
TextButton433.BackgroundColor = BrickColor.new("Black metallic")
TextButton433.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton433.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton433.BorderSizePixel = 0
TextButton433.ZIndex = 4
TextButton433.Font = Enum.Font.SourceSans
TextButton433.FontSize = Enum.FontSize.Size28
TextButton433.Text = "Up"
TextButton433.TextColor = BrickColor.new("Institutional white")
TextButton433.TextColor3 = Color3.new(1, 1, 1)
TextButton433.TextSize = 26
TextButton433.TextWrap = true
TextButton433.TextWrapped = true
TextButton434.Name = "Button2"
TextButton434.Parent = Frame432
TextButton434.Position = UDim2.new(0, 0, 0.340108037, 0)
TextButton434.Size = UDim2.new(1, 0, -0.0510674417, 35)
TextButton434.BackgroundColor = BrickColor.new("Black metallic")
TextButton434.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton434.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton434.BorderSizePixel = 0
TextButton434.ZIndex = 4
TextButton434.Font = Enum.Font.SourceSans
TextButton434.FontSize = Enum.FontSize.Size28
TextButton434.Text = "Down"
TextButton434.TextColor = BrickColor.new("Institutional white")
TextButton434.TextColor3 = Color3.new(1, 1, 1)
TextButton434.TextSize = 26
TextButton434.TextWrap = true
TextButton434.TextWrapped = true
TextButton435.Name = "Button3"
TextButton435.Parent = Frame432
TextButton435.Position = UDim2.new(0, 0, 0.681444347, 0)
TextButton435.Size = UDim2.new(1, 0, -0.0738480985, 35)
TextButton435.BackgroundColor = BrickColor.new("Black metallic")
TextButton435.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TextButton435.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton435.BorderSizePixel = 0
TextButton435.ZIndex = 4
TextButton435.Font = Enum.Font.SourceSans
TextButton435.FontSize = Enum.FontSize.Size28
TextButton435.Text = "Zero"
TextButton435.TextColor = BrickColor.new("Institutional white")
TextButton435.TextColor3 = Color3.new(1, 1, 1)
TextButton435.TextSize = 26
TextButton435.TextWrap = true
TextButton435.TextWrapped = true
LocalScript436.Name = "Effect"
LocalScript436.Parent = Frame430
table.insert(cors,sandbox(LocalScript436,function()
local drop = script.Parent
local menu = drop.Menu
local open = menu.Visible
local selection = drop.Selection


function trigger()
	if not open then
		
		script.Parent.Menu.Visible = false
		script.Parent.Menu.Visible = false
		open = true
	else
	
		script.Parent.Menu.Visible = true
		script.Parent.Menu.Visible = true
		open = false
	end
end

selection.MouseButton1Click:Connect(trigger)

for _, button in pairs(menu:GetChildren()) do
	if button:IsA("TextButton") then
		button.MouseEnter:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseLeave:Connect(function()
			button.BackgroundTransparency = 0
		end)
		button.MouseButton1Click:Connect(function()
			selection.Text = button.Text
			trigger()
		end)
	end
end
end))
TextLabel437.Name = "Anti Aimbot angles"
TextLabel437.Parent = Frame409
TextLabel437.Position = UDim2.new(0.0361394361, 0, -0.00979359634, 0)
TextLabel437.Size = UDim2.new(0, 202, 0, 10)
TextLabel437.Active = true
TextLabel437.BackgroundColor = BrickColor.new("Really black")
TextLabel437.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel437.BorderColor = BrickColor.new("Really black")
TextLabel437.BorderColor3 = Color3.new(0, 0, 0)
TextLabel437.BorderSizePixel = 0
TextLabel437.ZIndex = 2
TextLabel437.Font = Enum.Font.SourceSansBold
TextLabel437.FontSize = Enum.FontSize.Size28
TextLabel437.Text = "Anti Aimbot angles"
TextLabel437.TextColor = BrickColor.new("Mid gray")
TextLabel437.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel437.TextSize = 28
TextLabel437.TextWrap = true
TextLabel437.TextWrapped = true
Frame438.Name = "OtherTab"
Frame438.Parent = Frame385
Frame438.Position = UDim2.new(0.526000082, 0, 0.711140096, 0)
Frame438.Size = UDim2.new(0, 424, 0, 279)
Frame438.BackgroundColor = BrickColor.new("Really black")
Frame438.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame438.BorderColor = BrickColor.new("Dirt brown")
Frame438.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame438.BorderSizePixel = 2
ImageButton439.Name = "Fakeduck"
ImageButton439.Parent = Frame438
ImageButton439.Position = UDim2.new(0.0909999982, 0, 0.298999995, 0)
ImageButton439.Size = UDim2.new(0, 12, 0, 12)
ImageButton439.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton439.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton439.BorderColor = BrickColor.new("Really black")
ImageButton439.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton439.ZIndex = 999
ImageButton439.Image = "rbxassetid://5761429802"
ImageButton439.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton439.ImageTransparency = 0.25
TextLabel440.Name = "Fakeduck"
TextLabel440.Parent = ImageButton439
TextLabel440.Position = UDim2.new(3.65599561, 0, 0, -6)
TextLabel440.Size = UDim2.new(0, 341, 0, 20)
TextLabel440.BackgroundColor = BrickColor.new("Institutional white")
TextLabel440.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel440.BackgroundTransparency = 1
TextLabel440.Font = Enum.Font.SourceSans
TextLabel440.FontSize = Enum.FontSize.Size28
TextLabel440.Text = "Fake duck"
TextLabel440.TextColor = BrickColor.new("Institutional white")
TextLabel440.TextColor3 = Color3.new(1, 1, 1)
TextLabel440.TextSize = 26
TextLabel440.TextWrap = true
TextLabel440.TextWrapped = true
TextLabel440.TextXAlignment = Enum.TextXAlignment.Left
LocalScript441.Name = "Function"
LocalScript441.Parent = ImageButton439
table.insert(cors,sandbox(LocalScript441,function()
local button = script.Parent
local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
end

		
end	
button.Activated:Connect(onButtonActivated)
end))
ImageButton442.Name = "p1000000"
ImageButton442.Parent = Frame438
ImageButton442.Position = UDim2.new(0.0909999982, 0, 0.194942653, 0)
ImageButton442.Size = UDim2.new(0, 12, 0, 12)
ImageButton442.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton442.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton442.BorderColor = BrickColor.new("Really black")
ImageButton442.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton442.ZIndex = 999
ImageButton442.Image = "rbxassetid://5761429802"
ImageButton442.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton442.ImageTransparency = 0.25
TextLabel443.Name = "p1000000"
TextLabel443.Parent = ImageButton442
TextLabel443.Position = UDim2.new(3.65599561, 0, 0, -6)
TextLabel443.Size = UDim2.new(0, 341, 0, 20)
TextLabel443.BackgroundColor = BrickColor.new("Institutional white")
TextLabel443.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel443.BackgroundTransparency = 1
TextLabel443.Font = Enum.Font.SourceSans
TextLabel443.FontSize = Enum.FontSize.Size28
TextLabel443.Text = "Teleport anti aimbot (epilepsy)"
TextLabel443.TextColor = BrickColor.new("Institutional white")
TextLabel443.TextColor3 = Color3.new(1, 1, 1)
TextLabel443.TextSize = 26
TextLabel443.TextWrap = true
TextLabel443.TextWrapped = true
TextLabel443.TextXAlignment = Enum.TextXAlignment.Left
LocalScript444.Name = "Function"
LocalScript444.Parent = ImageButton442
table.insert(cors,sandbox(LocalScript444,function()
local button = script.Parent
local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		while wait() do 
			game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			game.Players.LocalPlayer.Character.HumanoidRootPart.Position = game.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0,0,0)
			game.Players.LocalPlayer.Character.Humanoid.CameraOffset = Vector3.new(0,0,0)
			wait()
			game.Players.LocalPlayer.Character.HumanoidRootPart.Position = game.Players.LocalPlayer.Character.Head.Position + Vector3.new(0,1000,0)
			game.Players.LocalPlayer.Character.Humanoid.CameraOffset = Vector3.new(0,1000,0)
		end
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
end

		
end	
button.Activated:Connect(onButtonActivated)
end))
ImageButton445.Name = "Nohead"
ImageButton445.Parent = Frame438
ImageButton445.Position = UDim2.new(0.0909999982, 0, 0.0909999982, 0)
ImageButton445.Size = UDim2.new(0, 12, 0, 12)
ImageButton445.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton445.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton445.BorderColor = BrickColor.new("Really black")
ImageButton445.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton445.ZIndex = 999
ImageButton445.Image = "rbxassetid://5761429802"
ImageButton445.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton445.ImageTransparency = 0.25
TextLabel446.Name = "Nohead"
TextLabel446.Parent = ImageButton445
TextLabel446.Position = UDim2.new(3.6559999, 0, 0, -6)
TextLabel446.Size = UDim2.new(0, 324, 0, 20)
TextLabel446.BackgroundColor = BrickColor.new("Institutional white")
TextLabel446.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel446.BackgroundTransparency = 1
TextLabel446.Font = Enum.Font.SourceSans
TextLabel446.FontSize = Enum.FontSize.Size28
TextLabel446.Text = "Remove head"
TextLabel446.TextColor = BrickColor.new("Institutional white")
TextLabel446.TextColor3 = Color3.new(1, 1, 1)
TextLabel446.TextSize = 26
TextLabel446.TextWrap = true
TextLabel446.TextWrapped = true
TextLabel446.TextXAlignment = Enum.TextXAlignment.Left
LocalScript447.Name = "Function"
LocalScript447.Parent = ImageButton445
table.insert(cors,sandbox(LocalScript447,function()
local button = script.Parent
local toggled = false
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer


local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		game.Players.LocalPlayer.Character:FindFirstChild('FakeHead'):Destroy()
		game.Players.LocalPlayer.Character:FindFirstChild('HeadHB'):Destroy()	
		while toggled == true do
			wait()
			pcall(function()
				game.Players.LocalPlayer.Character:FindFirstChild('FakeHead'):Destroy()
				game.Players.LocalPlayer.Character:FindFirstChild('HeadHB'):Destroy()
			end)				
		end		
	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		script.Parent.Parent.Parent.Parent.Parent.Parent.Parent.tags.Nohead.Visible = false
end

		
end	
button.Activated:Connect(onButtonActivated)
end))
TextLabel448.Name = "Other"
TextLabel448.Parent = Frame438
TextLabel448.Position = UDim2.new(0.0361394361, 0, -0.0417935476, 0)
TextLabel448.Size = UDim2.new(0, 68, 0, 12)
TextLabel448.Active = true
TextLabel448.BackgroundColor = BrickColor.new("Really black")
TextLabel448.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel448.BorderColor = BrickColor.new("Really black")
TextLabel448.BorderColor3 = Color3.new(0, 0, 0)
TextLabel448.BorderSizePixel = 0
TextLabel448.ZIndex = 2
TextLabel448.Font = Enum.Font.SourceSansBold
TextLabel448.FontSize = Enum.FontSize.Size28
TextLabel448.Text = "Other"
TextLabel448.TextColor = BrickColor.new("Mid gray")
TextLabel448.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel448.TextSize = 28
TextLabel448.TextWrap = true
TextLabel448.TextWrapped = true
ImageButton449.Name = "Slide"
ImageButton449.Parent = Frame438
ImageButton449.Position = UDim2.new(0.0909999982, 0, 0.402942657, 0)
ImageButton449.Size = UDim2.new(0, 12, 0, 12)
ImageButton449.BackgroundColor = BrickColor.new("Dark taupe")
ImageButton449.BackgroundColor3 = Color3.new(0.290196, 0.290196, 0.290196)
ImageButton449.BorderColor = BrickColor.new("Really black")
ImageButton449.BorderColor3 = Color3.new(0.105882, 0.105882, 0.105882)
ImageButton449.ZIndex = 999
ImageButton449.Image = "rbxassetid://5761429802"
ImageButton449.ImageColor3 = Color3.new(0.611765, 0.611765, 0.611765)
ImageButton449.ImageTransparency = 0.25
TextLabel450.Name = "Slide"
TextLabel450.Parent = ImageButton449
TextLabel450.Position = UDim2.new(3.65599561, 0, 0, -6)
TextLabel450.Size = UDim2.new(0, 341, 0, 20)
TextLabel450.BackgroundColor = BrickColor.new("Institutional white")
TextLabel450.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel450.BackgroundTransparency = 1
TextLabel450.Font = Enum.Font.SourceSans
TextLabel450.FontSize = Enum.FontSize.Size28
TextLabel450.Text = "Slide walk"
TextLabel450.TextColor = BrickColor.new("Institutional white")
TextLabel450.TextColor3 = Color3.new(1, 1, 1)
TextLabel450.TextSize = 26
TextLabel450.TextWrap = true
TextLabel450.TextWrapped = true
TextLabel450.TextXAlignment = Enum.TextXAlignment.Left
LocalScript451.Parent = ImageButton449
table.insert(cors,sandbox(LocalScript451,function()
local button = script.Parent
local player = game.Players.LocalPlayer

local toggled = false
local function onButtonActivated()
	if toggled == false then
		toggled = true
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(181, 255, 42)
		while toggled do
			player.Character.Animate.Disabled = false
			wait(1/100)
		end
 	else
		toggled = false
		script.Parent.BackgroundTransparency = 0
		script.Parent.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
		player.Character.Animate.Disabled = true
	end
end

button.Activated:Connect(onButtonActivated)



end))
Frame452.Name = "Legit"
Frame452.Parent = Frame18
Frame452.Position = UDim2.new(0, 0, 0.284013182, 0)
Frame452.Size = UDim2.new(0, 163, 0, 142)
Frame452.BackgroundColor = BrickColor.new("Really black")
Frame452.BackgroundColor3 = Color3.new(0, 0, 0)
Frame452.BorderColor = BrickColor.new("Really black")
Frame452.BorderColor3 = Color3.new(0, 0, 0)
Frame452.BorderSizePixel = 0
LocalScript453.Name = "Selected"
LocalScript453.Parent = Frame452
table.insert(cors,sandbox(LocalScript453,function()
local button = script.Parent.Icon


local function onMouseEntered()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.Icon.ImageColor3 ~= Color3.new(1, 1, 1)then
				script.Parent.Icon.ImageColor3 = Color3.new(1, 1, 1)
			end
		end
		button.Activated:Connect(onButtonActivated)
	end
	
end
local function onMouseLeft()
	if script.Parent.Main.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end

     
	
button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton454.Name = "Icon"
ImageButton454.Parent = Frame452
ImageButton454.Position = UDim2.new(0.0104141701, 0, 0.103171334, 0)
ImageButton454.Size = UDim2.new(0, 161, 0, 111)
ImageButton454.BackgroundColor = BrickColor.new("Really black")
ImageButton454.BackgroundColor3 = Color3.new(0, 0, 0)
ImageButton454.BackgroundTransparency = 1
ImageButton454.BorderColor = BrickColor.new("Really black")
ImageButton454.BorderColor3 = Color3.new(0, 0, 0)
ImageButton454.ZIndex = 100
ImageButton454.Image = "rbxassetid://5750433241"
ImageButton454.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton454.ScaleType = Enum.ScaleType.Fit
Frame455.Name = "Side Border"
Frame455.Parent = Frame452
Frame455.Position = UDim2.new(1, 0, -0.00644909497, 0)
Frame455.Size = UDim2.new(0, 3, 0, 145)
Frame455.BackgroundColor = BrickColor.new("Dirt brown")
Frame455.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame455.BorderSizePixel = 0
Frame455.ZIndex = 2
Frame456.Name = "Other border"
Frame456.Parent = Frame452
Frame456.Position = UDim2.new(0, 0, 0, -3)
Frame456.Visible = false
Frame456.Size = UDim2.new(0, 166, 0, 3)
Frame456.BackgroundColor = BrickColor.new("Dirt brown")
Frame456.BackgroundColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame456.BorderSizePixel = 0
Frame456.ZIndex = 3
Frame457.Name = "Main"
Frame457.Parent = Frame452
Frame457.Position = UDim2.new(1.12899995, 0, -1.93799996, 0)
Frame457.Visible = false
Frame457.Size = UDim2.new(0, 941, 0, 993)
Frame457.BackgroundColor = BrickColor.new("Lime green")
Frame457.BackgroundColor3 = Color3.new(0, 1, 0.14902)
Frame457.BackgroundTransparency = 1
Frame457.BorderSizePixel = 0
Frame458.Name = "SNIPER"
Frame458.Parent = Frame457
Frame458.Position = UDim2.new(0.00116810005, 0, 2.85814167e-05, 0)
Frame458.Visible = false
Frame458.Size = UDim2.new(0, 937, 0, 996)
Frame458.BackgroundColor = BrickColor.new("Institutional white")
Frame458.BackgroundColor3 = Color3.new(1, 1, 1)
Frame458.BackgroundTransparency = 1
Frame459.Name = "AimbotTab"
Frame459.Parent = Frame458
Frame459.Position = UDim2.new(0.0236982461, 0, 0.169949651, 0)
Frame459.Size = UDim2.new(0, 424, 0, 816)
Frame459.BackgroundColor = BrickColor.new("Really black")
Frame459.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame459.BorderColor = BrickColor.new("Dirt brown")
Frame459.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame459.BorderSizePixel = 2
TextLabel460.Name = "Aimbot"
TextLabel460.Parent = Frame459
TextLabel460.Position = UDim2.new(0.0361394361, 0, -0.00979359355, 0)
TextLabel460.Size = UDim2.new(0, 78, 0, 10)
TextLabel460.Active = true
TextLabel460.BackgroundColor = BrickColor.new("Really black")
TextLabel460.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel460.BorderColor = BrickColor.new("Really black")
TextLabel460.BorderColor3 = Color3.new(0, 0, 0)
TextLabel460.BorderSizePixel = 0
TextLabel460.ZIndex = 2
TextLabel460.Font = Enum.Font.SourceSansBold
TextLabel460.FontSize = Enum.FontSize.Size28
TextLabel460.Text = "Aimbot"
TextLabel460.TextColor = BrickColor.new("Mid gray")
TextLabel460.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel460.TextSize = 28
TextLabel460.TextWrap = true
TextLabel460.TextWrapped = true
Frame461.Name = "OtherTab"
Frame461.Parent = Frame458
Frame461.Position = UDim2.new(0.526000082, 0, 0.711140096, 0)
Frame461.Size = UDim2.new(0, 424, 0, 278)
Frame461.BackgroundColor = BrickColor.new("Really black")
Frame461.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame461.BorderColor = BrickColor.new("Dirt brown")
Frame461.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame461.BorderSizePixel = 2
TextLabel462.Name = "Other"
TextLabel462.Parent = Frame461
TextLabel462.Position = UDim2.new(0.0361394361, 0, -0.0417935476, 0)
TextLabel462.Size = UDim2.new(0, 68, 0, 12)
TextLabel462.Active = true
TextLabel462.BackgroundColor = BrickColor.new("Really black")
TextLabel462.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel462.BorderColor = BrickColor.new("Really black")
TextLabel462.BorderColor3 = Color3.new(0, 0, 0)
TextLabel462.BorderSizePixel = 0
TextLabel462.ZIndex = 2
TextLabel462.Font = Enum.Font.SourceSansBold
TextLabel462.FontSize = Enum.FontSize.Size28
TextLabel462.Text = "Other"
TextLabel462.TextColor = BrickColor.new("Mid gray")
TextLabel462.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel462.TextSize = 28
TextLabel462.TextWrap = true
TextLabel462.TextWrapped = true
Frame463.Name = "TriggerbotTab"
Frame463.Parent = Frame458
Frame463.Position = UDim2.new(0.526000082, 0, 0.169949651, 0)
Frame463.Size = UDim2.new(0, 424, 0, 485)
Frame463.BackgroundColor = BrickColor.new("Really black")
Frame463.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame463.BorderColor = BrickColor.new("Dirt brown")
Frame463.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame463.BorderSizePixel = 2
TextLabel464.Name = "Triggerbot"
TextLabel464.Parent = Frame463
TextLabel464.Position = UDim2.new(0.0361394361, 0, -0.0180409849, 0)
TextLabel464.Size = UDim2.new(0, 114, 0, 10)
TextLabel464.Active = true
TextLabel464.BackgroundColor = BrickColor.new("Really black")
TextLabel464.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel464.BorderColor = BrickColor.new("Really black")
TextLabel464.BorderColor3 = Color3.new(0, 0, 0)
TextLabel464.BorderSizePixel = 0
TextLabel464.ZIndex = 2
TextLabel464.Font = Enum.Font.SourceSansBold
TextLabel464.FontSize = Enum.FontSize.Size28
TextLabel464.Text = "Triggerbot"
TextLabel464.TextColor = BrickColor.new("Mid gray")
TextLabel464.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel464.TextSize = 28
TextLabel464.TextWrap = true
TextLabel464.TextWrapped = true
Frame465.Name = "MG"
Frame465.Parent = Frame457
Frame465.Position = UDim2.new(0.00116810005, 0, 2.85814167e-05, 0)
Frame465.Visible = false
Frame465.Size = UDim2.new(0, 937, 0, 996)
Frame465.BackgroundColor = BrickColor.new("Institutional white")
Frame465.BackgroundColor3 = Color3.new(1, 1, 1)
Frame465.BackgroundTransparency = 1
Frame466.Name = "AimbotTab"
Frame466.Parent = Frame465
Frame466.Position = UDim2.new(0.0236982461, 0, 0.169949651, 0)
Frame466.Size = UDim2.new(0, 424, 0, 816)
Frame466.BackgroundColor = BrickColor.new("Really black")
Frame466.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame466.BorderColor = BrickColor.new("Dirt brown")
Frame466.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame466.BorderSizePixel = 2
TextLabel467.Name = "Aimbot"
TextLabel467.Parent = Frame466
TextLabel467.Position = UDim2.new(0.0361394361, 0, -0.00979359355, 0)
TextLabel467.Size = UDim2.new(0, 78, 0, 10)
TextLabel467.Active = true
TextLabel467.BackgroundColor = BrickColor.new("Really black")
TextLabel467.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel467.BorderColor = BrickColor.new("Really black")
TextLabel467.BorderColor3 = Color3.new(0, 0, 0)
TextLabel467.BorderSizePixel = 0
TextLabel467.ZIndex = 2
TextLabel467.Font = Enum.Font.SourceSansBold
TextLabel467.FontSize = Enum.FontSize.Size28
TextLabel467.Text = "Aimbot"
TextLabel467.TextColor = BrickColor.new("Mid gray")
TextLabel467.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel467.TextSize = 28
TextLabel467.TextWrap = true
TextLabel467.TextWrapped = true
Frame468.Name = "OtherTab"
Frame468.Parent = Frame465
Frame468.Position = UDim2.new(0.526000082, 0, 0.711140096, 0)
Frame468.Size = UDim2.new(0, 424, 0, 278)
Frame468.BackgroundColor = BrickColor.new("Really black")
Frame468.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame468.BorderColor = BrickColor.new("Dirt brown")
Frame468.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame468.BorderSizePixel = 2
TextLabel469.Name = "Other"
TextLabel469.Parent = Frame468
TextLabel469.Position = UDim2.new(0.0361394361, 0, -0.0417935476, 0)
TextLabel469.Size = UDim2.new(0, 68, 0, 12)
TextLabel469.Active = true
TextLabel469.BackgroundColor = BrickColor.new("Really black")
TextLabel469.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel469.BorderColor = BrickColor.new("Really black")
TextLabel469.BorderColor3 = Color3.new(0, 0, 0)
TextLabel469.BorderSizePixel = 0
TextLabel469.ZIndex = 2
TextLabel469.Font = Enum.Font.SourceSansBold
TextLabel469.FontSize = Enum.FontSize.Size28
TextLabel469.Text = "Other"
TextLabel469.TextColor = BrickColor.new("Mid gray")
TextLabel469.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel469.TextSize = 28
TextLabel469.TextWrap = true
TextLabel469.TextWrapped = true
Frame470.Name = "TriggerbotTab"
Frame470.Parent = Frame465
Frame470.Position = UDim2.new(0.526000082, 0, 0.169949651, 0)
Frame470.Size = UDim2.new(0, 424, 0, 485)
Frame470.BackgroundColor = BrickColor.new("Really black")
Frame470.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame470.BorderColor = BrickColor.new("Dirt brown")
Frame470.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame470.BorderSizePixel = 2
TextLabel471.Name = "Triggerbot"
TextLabel471.Parent = Frame470
TextLabel471.Position = UDim2.new(0.0361394361, 0, -0.0180409849, 0)
TextLabel471.Size = UDim2.new(0, 114, 0, 10)
TextLabel471.Active = true
TextLabel471.BackgroundColor = BrickColor.new("Really black")
TextLabel471.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel471.BorderColor = BrickColor.new("Really black")
TextLabel471.BorderColor3 = Color3.new(0, 0, 0)
TextLabel471.BorderSizePixel = 0
TextLabel471.ZIndex = 2
TextLabel471.Font = Enum.Font.SourceSansBold
TextLabel471.FontSize = Enum.FontSize.Size28
TextLabel471.Text = "Triggerbot"
TextLabel471.TextColor = BrickColor.new("Mid gray")
TextLabel471.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel471.TextSize = 28
TextLabel471.TextWrap = true
TextLabel471.TextWrapped = true
Frame472.Name = "SHOTGUN"
Frame472.Parent = Frame457
Frame472.Position = UDim2.new(0.00116810005, 0, 2.85814167e-05, 0)
Frame472.Visible = false
Frame472.Size = UDim2.new(0, 937, 0, 996)
Frame472.BackgroundColor = BrickColor.new("Institutional white")
Frame472.BackgroundColor3 = Color3.new(1, 1, 1)
Frame472.BackgroundTransparency = 1
Frame473.Name = "AimbotTab"
Frame473.Parent = Frame472
Frame473.Position = UDim2.new(0.0236982461, 0, 0.169949651, 0)
Frame473.Size = UDim2.new(0, 424, 0, 816)
Frame473.BackgroundColor = BrickColor.new("Really black")
Frame473.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame473.BorderColor = BrickColor.new("Dirt brown")
Frame473.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame473.BorderSizePixel = 2
TextLabel474.Name = "Aimbot"
TextLabel474.Parent = Frame473
TextLabel474.Position = UDim2.new(0.0361394361, 0, -0.00979359355, 0)
TextLabel474.Size = UDim2.new(0, 78, 0, 10)
TextLabel474.Active = true
TextLabel474.BackgroundColor = BrickColor.new("Really black")
TextLabel474.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel474.BorderColor = BrickColor.new("Really black")
TextLabel474.BorderColor3 = Color3.new(0, 0, 0)
TextLabel474.BorderSizePixel = 0
TextLabel474.ZIndex = 2
TextLabel474.Font = Enum.Font.SourceSansBold
TextLabel474.FontSize = Enum.FontSize.Size28
TextLabel474.Text = "Aimbot"
TextLabel474.TextColor = BrickColor.new("Mid gray")
TextLabel474.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel474.TextSize = 28
TextLabel474.TextWrap = true
TextLabel474.TextWrapped = true
Frame475.Name = "OtherTab"
Frame475.Parent = Frame472
Frame475.Position = UDim2.new(0.526000082, 0, 0.711140096, 0)
Frame475.Size = UDim2.new(0, 424, 0, 278)
Frame475.BackgroundColor = BrickColor.new("Really black")
Frame475.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame475.BorderColor = BrickColor.new("Dirt brown")
Frame475.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame475.BorderSizePixel = 2
TextLabel476.Name = "Other"
TextLabel476.Parent = Frame475
TextLabel476.Position = UDim2.new(0.0361394361, 0, -0.0417935476, 0)
TextLabel476.Size = UDim2.new(0, 68, 0, 12)
TextLabel476.Active = true
TextLabel476.BackgroundColor = BrickColor.new("Really black")
TextLabel476.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel476.BorderColor = BrickColor.new("Really black")
TextLabel476.BorderColor3 = Color3.new(0, 0, 0)
TextLabel476.BorderSizePixel = 0
TextLabel476.ZIndex = 2
TextLabel476.Font = Enum.Font.SourceSansBold
TextLabel476.FontSize = Enum.FontSize.Size28
TextLabel476.Text = "Other"
TextLabel476.TextColor = BrickColor.new("Mid gray")
TextLabel476.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel476.TextSize = 28
TextLabel476.TextWrap = true
TextLabel476.TextWrapped = true
Frame477.Name = "TriggerbotTab"
Frame477.Parent = Frame472
Frame477.Position = UDim2.new(0.526000082, 0, 0.169949651, 0)
Frame477.Size = UDim2.new(0, 424, 0, 485)
Frame477.BackgroundColor = BrickColor.new("Really black")
Frame477.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame477.BorderColor = BrickColor.new("Dirt brown")
Frame477.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame477.BorderSizePixel = 2
TextLabel478.Name = "Triggerbot"
TextLabel478.Parent = Frame477
TextLabel478.Position = UDim2.new(0.0361394361, 0, -0.0180409849, 0)
TextLabel478.Size = UDim2.new(0, 114, 0, 10)
TextLabel478.Active = true
TextLabel478.BackgroundColor = BrickColor.new("Really black")
TextLabel478.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel478.BorderColor = BrickColor.new("Really black")
TextLabel478.BorderColor3 = Color3.new(0, 0, 0)
TextLabel478.BorderSizePixel = 0
TextLabel478.ZIndex = 2
TextLabel478.Font = Enum.Font.SourceSansBold
TextLabel478.FontSize = Enum.FontSize.Size28
TextLabel478.Text = "Triggerbot"
TextLabel478.TextColor = BrickColor.new("Mid gray")
TextLabel478.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel478.TextSize = 28
TextLabel478.TextWrap = true
TextLabel478.TextWrapped = true
Frame479.Name = "RIFLE"
Frame479.Parent = Frame457
Frame479.Position = UDim2.new(0.00116810005, 0, 2.85814167e-05, 0)
Frame479.Visible = false
Frame479.Size = UDim2.new(0, 937, 0, 996)
Frame479.BackgroundColor = BrickColor.new("Institutional white")
Frame479.BackgroundColor3 = Color3.new(1, 1, 1)
Frame479.BackgroundTransparency = 1
Frame480.Name = "AimbotTab"
Frame480.Parent = Frame479
Frame480.Position = UDim2.new(0.0236982461, 0, 0.169949651, 0)
Frame480.Size = UDim2.new(0, 424, 0, 816)
Frame480.BackgroundColor = BrickColor.new("Really black")
Frame480.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame480.BorderColor = BrickColor.new("Dirt brown")
Frame480.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame480.BorderSizePixel = 2
TextLabel481.Name = "Aimbot"
TextLabel481.Parent = Frame480
TextLabel481.Position = UDim2.new(0.0361394361, 0, -0.00979359355, 0)
TextLabel481.Size = UDim2.new(0, 78, 0, 10)
TextLabel481.Active = true
TextLabel481.BackgroundColor = BrickColor.new("Really black")
TextLabel481.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel481.BorderColor = BrickColor.new("Really black")
TextLabel481.BorderColor3 = Color3.new(0, 0, 0)
TextLabel481.BorderSizePixel = 0
TextLabel481.ZIndex = 2
TextLabel481.Font = Enum.Font.SourceSansBold
TextLabel481.FontSize = Enum.FontSize.Size28
TextLabel481.Text = "Aimbot"
TextLabel481.TextColor = BrickColor.new("Mid gray")
TextLabel481.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel481.TextSize = 28
TextLabel481.TextWrap = true
TextLabel481.TextWrapped = true
Frame482.Name = "OtherTab"
Frame482.Parent = Frame479
Frame482.Position = UDim2.new(0.526000082, 0, 0.711140096, 0)
Frame482.Size = UDim2.new(0, 424, 0, 278)
Frame482.BackgroundColor = BrickColor.new("Really black")
Frame482.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame482.BorderColor = BrickColor.new("Dirt brown")
Frame482.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame482.BorderSizePixel = 2
TextLabel483.Name = "Other"
TextLabel483.Parent = Frame482
TextLabel483.Position = UDim2.new(0.0361394361, 0, -0.0417935476, 0)
TextLabel483.Size = UDim2.new(0, 68, 0, 12)
TextLabel483.Active = true
TextLabel483.BackgroundColor = BrickColor.new("Really black")
TextLabel483.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel483.BorderColor = BrickColor.new("Really black")
TextLabel483.BorderColor3 = Color3.new(0, 0, 0)
TextLabel483.BorderSizePixel = 0
TextLabel483.ZIndex = 2
TextLabel483.Font = Enum.Font.SourceSansBold
TextLabel483.FontSize = Enum.FontSize.Size28
TextLabel483.Text = "Other"
TextLabel483.TextColor = BrickColor.new("Mid gray")
TextLabel483.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel483.TextSize = 28
TextLabel483.TextWrap = true
TextLabel483.TextWrapped = true
Frame484.Name = "TriggerbotTab"
Frame484.Parent = Frame479
Frame484.Position = UDim2.new(0.526000082, 0, 0.169949651, 0)
Frame484.Size = UDim2.new(0, 424, 0, 485)
Frame484.BackgroundColor = BrickColor.new("Really black")
Frame484.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame484.BorderColor = BrickColor.new("Dirt brown")
Frame484.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame484.BorderSizePixel = 2
TextLabel485.Name = "Triggerbot"
TextLabel485.Parent = Frame484
TextLabel485.Position = UDim2.new(0.0361394361, 0, -0.0180409849, 0)
TextLabel485.Size = UDim2.new(0, 114, 0, 10)
TextLabel485.Active = true
TextLabel485.BackgroundColor = BrickColor.new("Really black")
TextLabel485.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel485.BorderColor = BrickColor.new("Really black")
TextLabel485.BorderColor3 = Color3.new(0, 0, 0)
TextLabel485.BorderSizePixel = 0
TextLabel485.ZIndex = 2
TextLabel485.Font = Enum.Font.SourceSansBold
TextLabel485.FontSize = Enum.FontSize.Size28
TextLabel485.Text = "Triggerbot"
TextLabel485.TextColor = BrickColor.new("Mid gray")
TextLabel485.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel485.TextSize = 28
TextLabel485.TextWrap = true
TextLabel485.TextWrapped = true
Frame486.Name = "SMG"
Frame486.Parent = Frame457
Frame486.Position = UDim2.new(0.00116810005, 0, 2.85814167e-05, 0)
Frame486.Visible = false
Frame486.Size = UDim2.new(0, 937, 0, 996)
Frame486.BackgroundColor = BrickColor.new("Institutional white")
Frame486.BackgroundColor3 = Color3.new(1, 1, 1)
Frame486.BackgroundTransparency = 1
Frame487.Name = "AimbotTab"
Frame487.Parent = Frame486
Frame487.Position = UDim2.new(0.0236982461, 0, 0.169949651, 0)
Frame487.Size = UDim2.new(0, 424, 0, 816)
Frame487.BackgroundColor = BrickColor.new("Really black")
Frame487.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame487.BorderColor = BrickColor.new("Dirt brown")
Frame487.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame487.BorderSizePixel = 2
TextLabel488.Name = "Aimbot"
TextLabel488.Parent = Frame487
TextLabel488.Position = UDim2.new(0.0361394361, 0, -0.00979359355, 0)
TextLabel488.Size = UDim2.new(0, 78, 0, 10)
TextLabel488.Active = true
TextLabel488.BackgroundColor = BrickColor.new("Really black")
TextLabel488.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel488.BorderColor = BrickColor.new("Really black")
TextLabel488.BorderColor3 = Color3.new(0, 0, 0)
TextLabel488.BorderSizePixel = 0
TextLabel488.ZIndex = 2
TextLabel488.Font = Enum.Font.SourceSansBold
TextLabel488.FontSize = Enum.FontSize.Size28
TextLabel488.Text = "Aimbot"
TextLabel488.TextColor = BrickColor.new("Mid gray")
TextLabel488.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel488.TextSize = 28
TextLabel488.TextWrap = true
TextLabel488.TextWrapped = true
Frame489.Name = "OtherTab"
Frame489.Parent = Frame486
Frame489.Position = UDim2.new(0.526000082, 0, 0.711140096, 0)
Frame489.Size = UDim2.new(0, 424, 0, 278)
Frame489.BackgroundColor = BrickColor.new("Really black")
Frame489.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame489.BorderColor = BrickColor.new("Dirt brown")
Frame489.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame489.BorderSizePixel = 2
TextLabel490.Name = "Other"
TextLabel490.Parent = Frame489
TextLabel490.Position = UDim2.new(0.0361394361, 0, -0.0417935476, 0)
TextLabel490.Size = UDim2.new(0, 68, 0, 12)
TextLabel490.Active = true
TextLabel490.BackgroundColor = BrickColor.new("Really black")
TextLabel490.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel490.BorderColor = BrickColor.new("Really black")
TextLabel490.BorderColor3 = Color3.new(0, 0, 0)
TextLabel490.BorderSizePixel = 0
TextLabel490.ZIndex = 2
TextLabel490.Font = Enum.Font.SourceSansBold
TextLabel490.FontSize = Enum.FontSize.Size28
TextLabel490.Text = "Other"
TextLabel490.TextColor = BrickColor.new("Mid gray")
TextLabel490.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel490.TextSize = 28
TextLabel490.TextWrap = true
TextLabel490.TextWrapped = true
Frame491.Name = "TriggerbotTab"
Frame491.Parent = Frame486
Frame491.Position = UDim2.new(0.526000082, 0, 0.169949651, 0)
Frame491.Size = UDim2.new(0, 424, 0, 485)
Frame491.BackgroundColor = BrickColor.new("Really black")
Frame491.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame491.BorderColor = BrickColor.new("Dirt brown")
Frame491.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame491.BorderSizePixel = 2
TextLabel492.Name = "Triggerbot"
TextLabel492.Parent = Frame491
TextLabel492.Position = UDim2.new(0.0361394361, 0, -0.0180409849, 0)
TextLabel492.Size = UDim2.new(0, 114, 0, 10)
TextLabel492.Active = true
TextLabel492.BackgroundColor = BrickColor.new("Really black")
TextLabel492.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel492.BorderColor = BrickColor.new("Really black")
TextLabel492.BorderColor3 = Color3.new(0, 0, 0)
TextLabel492.BorderSizePixel = 0
TextLabel492.ZIndex = 2
TextLabel492.Font = Enum.Font.SourceSansBold
TextLabel492.FontSize = Enum.FontSize.Size28
TextLabel492.Text = "Triggerbot"
TextLabel492.TextColor = BrickColor.new("Mid gray")
TextLabel492.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel492.TextSize = 28
TextLabel492.TextWrap = true
TextLabel492.TextWrapped = true
Frame493.Name = "weaponbar"
Frame493.Parent = Frame457
Frame493.Position = UDim2.new(0.0233793836, 0, 0.0241691843, 0)
Frame493.Size = UDim2.new(0, 896, 0, 100)
Frame493.BackgroundColor = BrickColor.new("Really black")
Frame493.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame493.BorderColor = BrickColor.new("Dirt brown")
Frame493.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame493.BorderSizePixel = 2
ImageButton494.Name = "P90"
ImageButton494.Parent = Frame493
ImageButton494.Position = UDim2.new(0.148478106, 0, 0, 0)
ImageButton494.Size = UDim2.new(0, 120, 0, 100)
ImageButton494.BackgroundColor = BrickColor.new("Institutional white")
ImageButton494.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton494.BackgroundTransparency = 1
ImageButton494.Image = "rbxassetid://5878393149"
ImageButton494.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton494.ScaleType = Enum.ScaleType.Fit
LocalScript495.Name = "Selection"
LocalScript495.Parent = ImageButton494
table.insert(cors,sandbox(LocalScript495,function()
local button = script.Parent
function invis()
	script.Parent.Parent.Parent.PISTOL.Visible = false
	script.Parent.Parent.Parent.SMG.Visible = false
	script.Parent.Parent.Parent.RIFLE.Visible = false
	script.Parent.Parent.Parent.SHOTGUN.Visible = false
	script.Parent.Parent.Parent.MG.Visible = false
	script.Parent.Parent.Parent.SNIPER.Visible = false

	script.Parent.Parent.USP.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.SSG08.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.P90.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.NEGEV.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.MAG7.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.AK47.ImageColor3 = Color3.fromRGB(143, 143, 143)
end

local function onMouseEntered()
	if script.Parent.Parent.Parent.SMG.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.ImageColor3 ~= Color3.new(1, 1, 1)then
				invis()
				script.Parent.ImageColor3 = Color3.new(1, 1, 1)
				script.Parent.Parent.Parent.SMG.Visible = true
			end
		end
		button.Activated:Connect(onButtonActivated)
	end

end
local function onMouseLeft()
	if script.Parent.Parent.Parent.SMG.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end



button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton496.Name = "AK47"
ImageButton496.Parent = Frame493
ImageButton496.Position = UDim2.new(0.309966773, 0, 0, 0)
ImageButton496.Size = UDim2.new(0, 158, 0, 100)
ImageButton496.BackgroundColor = BrickColor.new("Institutional white")
ImageButton496.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton496.BackgroundTransparency = 1
ImageButton496.Image = "rbxassetid://5878392954"
ImageButton496.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton496.ScaleType = Enum.ScaleType.Fit
LocalScript497.Name = "Selection"
LocalScript497.Parent = ImageButton496
table.insert(cors,sandbox(LocalScript497,function()
local button = script.Parent
function invis()
	script.Parent.Parent.Parent.PISTOL.Visible = false
	script.Parent.Parent.Parent.SMG.Visible = false
	script.Parent.Parent.Parent.RIFLE.Visible = false
	script.Parent.Parent.Parent.SHOTGUN.Visible = false
	script.Parent.Parent.Parent.MG.Visible = false
	script.Parent.Parent.Parent.SNIPER.Visible = false
	
	script.Parent.Parent.USP.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.SSG08.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.P90.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.NEGEV.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.MAG7.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.AK47.ImageColor3 = Color3.fromRGB(143, 143, 143)
end


local function onMouseEntered()
	if script.Parent.Parent.Parent.RIFLE.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.ImageColor3 ~= Color3.new(1, 1, 1)then
				invis()
				script.Parent.ImageColor3 = Color3.new(1, 1, 1)
				script.Parent.Parent.Parent.RIFLE.Visible = true
			end
		end
		button.Activated:Connect(onButtonActivated)
	end

end
local function onMouseLeft()
	if script.Parent.Parent.Parent.RIFLE.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end



button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton498.Name = "MAG7"
ImageButton498.Parent = Frame493
ImageButton498.Position = UDim2.new(0.511922598, 0, 0, 0)
ImageButton498.Size = UDim2.new(0, 112, 0, 100)
ImageButton498.BackgroundColor = BrickColor.new("Institutional white")
ImageButton498.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton498.BackgroundTransparency = 1
ImageButton498.Image = "rbxassetid://5878392768"
ImageButton498.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton498.ScaleType = Enum.ScaleType.Fit
LocalScript499.Name = "Selection"
LocalScript499.Parent = ImageButton498
table.insert(cors,sandbox(LocalScript499,function()
local button = script.Parent
function invis()
	script.Parent.Parent.Parent.PISTOL.Visible = false
	script.Parent.Parent.Parent.SMG.Visible = false
	script.Parent.Parent.Parent.RIFLE.Visible = false
	script.Parent.Parent.Parent.SHOTGUN.Visible = false
	script.Parent.Parent.Parent.MG.Visible = false
	script.Parent.Parent.Parent.SNIPER.Visible = false

	script.Parent.Parent.USP.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.SSG08.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.P90.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.NEGEV.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.MAG7.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.AK47.ImageColor3 = Color3.fromRGB(143, 143, 143)
end

local function onMouseEntered()
	if script.Parent.Parent.Parent.SHOTGUN.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.ImageColor3 ~= Color3.new(1, 1, 1)then
				invis()
				script.Parent.ImageColor3 = Color3.new(1, 1, 1)			
				script.Parent.Parent.Parent.SHOTGUN.Visible = true
			end
		end
		button.Activated:Connect(onButtonActivated)
	end

end
local function onMouseLeft()
	if script.Parent.Parent.Parent.SHOTGUN.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end



button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton500.Name = "NEGEV"
ImageButton500.Parent = Frame493
ImageButton500.Position = UDim2.new(0.663954318, 0, 0, 0)
ImageButton500.Size = UDim2.new(0, 139, 0, 100)
ImageButton500.BackgroundColor = BrickColor.new("Institutional white")
ImageButton500.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton500.BackgroundTransparency = 1
ImageButton500.Image = "rbxassetid://5878392574"
ImageButton500.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton500.ScaleType = Enum.ScaleType.Fit
LocalScript501.Name = "Selection"
LocalScript501.Parent = ImageButton500
table.insert(cors,sandbox(LocalScript501,function()
local button = script.Parent
function invis()
	script.Parent.Parent.Parent.PISTOL.Visible = false
	script.Parent.Parent.Parent.SMG.Visible = false
	script.Parent.Parent.Parent.RIFLE.Visible = false
	script.Parent.Parent.Parent.SHOTGUN.Visible = false
	script.Parent.Parent.Parent.MG.Visible = false
	script.Parent.Parent.Parent.SNIPER.Visible = false

	script.Parent.Parent.USP.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.SSG08.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.P90.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.NEGEV.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.MAG7.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.AK47.ImageColor3 = Color3.fromRGB(143, 143, 143)
end

local function onMouseEntered()
	if script.Parent.Parent.Parent.MG.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.ImageColor3 ~= Color3.new(1, 1, 1)then
				invis()
				script.Parent.ImageColor3 = Color3.new(1, 1, 1)
				script.Parent.Parent.Parent.MG.Visible = true
			end
		end
		button.Activated:Connect(onButtonActivated)
	end

end
local function onMouseLeft()
	if script.Parent.Parent.Parent.MG.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end



button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton502.Name = "SSG08"
ImageButton502.Parent = Frame493
ImageButton502.Position = UDim2.new(0.836981773, 0, 0, 0)
ImageButton502.Size = UDim2.new(0, 137, 0, 100)
ImageButton502.BackgroundColor = BrickColor.new("Institutional white")
ImageButton502.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton502.BackgroundTransparency = 1
ImageButton502.Image = "rbxassetid://5878392436"
ImageButton502.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton502.ScaleType = Enum.ScaleType.Fit
LocalScript503.Name = "Selection"
LocalScript503.Parent = ImageButton502
table.insert(cors,sandbox(LocalScript503,function()
local button = script.Parent
function invis()
	script.Parent.Parent.Parent.PISTOL.Visible = false
	script.Parent.Parent.Parent.SMG.Visible = false
	script.Parent.Parent.Parent.RIFLE.Visible = false
	script.Parent.Parent.Parent.SHOTGUN.Visible = false
	script.Parent.Parent.Parent.MG.Visible = false
	script.Parent.Parent.Parent.SNIPER.Visible = false

	script.Parent.Parent.USP.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.SSG08.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.P90.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.NEGEV.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.MAG7.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.AK47.ImageColor3 = Color3.fromRGB(143, 143, 143)
end

local function onMouseEntered()
	if script.Parent.Parent.Parent.SNIPER.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.ImageColor3 ~= Color3.new(1, 1, 1)then
				invis()
				script.Parent.ImageColor3 = Color3.new(1, 1, 1)
				script.Parent.Parent.Parent.SNIPER.Visible = true
			end
		end
		button.Activated:Connect(onButtonActivated)
	end

end
local function onMouseLeft()
	if script.Parent.Parent.Parent.SNIPER.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end



button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
ImageButton504.Name = "USP"
ImageButton504.Parent = Frame493
ImageButton504.Position = UDim2.new(0.0174365733, 0, 0, 0)
ImageButton504.Size = UDim2.new(0, 96, 0, 100)
ImageButton504.BackgroundColor = BrickColor.new("Institutional white")
ImageButton504.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton504.BackgroundTransparency = 1
ImageButton504.Image = "rbxassetid://5878393387"
ImageButton504.ImageColor3 = Color3.new(0.560784, 0.560784, 0.560784)
ImageButton504.ScaleType = Enum.ScaleType.Fit
LocalScript505.Name = "Selection"
LocalScript505.Parent = ImageButton504
table.insert(cors,sandbox(LocalScript505,function()
local button = script.Parent
function invis()
	script.Parent.Parent.Parent.PISTOL.Visible = false
	script.Parent.Parent.Parent.SMG.Visible = false
	script.Parent.Parent.Parent.RIFLE.Visible = false
	script.Parent.Parent.Parent.SHOTGUN.Visible = false
	script.Parent.Parent.Parent.MG.Visible = false
	script.Parent.Parent.Parent.SNIPER.Visible = false

	script.Parent.Parent.USP.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.SSG08.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.P90.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.NEGEV.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.MAG7.ImageColor3 = Color3.fromRGB(143, 143, 143)
	script.Parent.Parent.AK47.ImageColor3 = Color3.fromRGB(143, 143, 143)
end

local function onMouseEntered()
	if script.Parent.Parent.Parent.PISTOL.Visible == false then
		button.ImageColor3 = Color3.fromRGB(168, 168, 168)
		local function onButtonActivated()
			if script.Parent.ImageColor3 ~= Color3.new(1, 1, 1)then
				invis()
				script.Parent.ImageColor3 = Color3.new(1, 1, 1)
				script.Parent.Parent.Parent.PISTOL.Visible = true
			end
		end
		button.Activated:Connect(onButtonActivated)
	end

end
local function onMouseLeft()
	if script.Parent.Parent.Parent.PISTOL.Visible == false then
		button.ImageColor3 = Color3.fromRGB(143, 143, 143)
	end
end



button.MouseEnter:Connect(onMouseEntered)
button.MouseLeave:Connect(onMouseLeft)


end))
Frame506.Name = "PISTOL"
Frame506.Parent = Frame457
Frame506.Position = UDim2.new(0.00116810005, 0, 2.85814167e-05, 0)
Frame506.Visible = false
Frame506.Size = UDim2.new(0, 937, 0, 996)
Frame506.BackgroundColor = BrickColor.new("Institutional white")
Frame506.BackgroundColor3 = Color3.new(1, 1, 1)
Frame506.BackgroundTransparency = 1
Frame507.Name = "AimbotTab"
Frame507.Parent = Frame506
Frame507.Position = UDim2.new(0.0236982461, 0, 0.169949651, 0)
Frame507.Size = UDim2.new(0, 424, 0, 816)
Frame507.BackgroundColor = BrickColor.new("Really black")
Frame507.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame507.BorderColor = BrickColor.new("Dirt brown")
Frame507.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame507.BorderSizePixel = 2
TextLabel508.Name = "Aimbot"
TextLabel508.Parent = Frame507
TextLabel508.Position = UDim2.new(0.0361394361, 0, -0.00979359355, 0)
TextLabel508.Size = UDim2.new(0, 78, 0, 10)
TextLabel508.Active = true
TextLabel508.BackgroundColor = BrickColor.new("Really black")
TextLabel508.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel508.BorderColor = BrickColor.new("Really black")
TextLabel508.BorderColor3 = Color3.new(0, 0, 0)
TextLabel508.BorderSizePixel = 0
TextLabel508.ZIndex = 2
TextLabel508.Font = Enum.Font.SourceSansBold
TextLabel508.FontSize = Enum.FontSize.Size28
TextLabel508.Text = "Aimbot"
TextLabel508.TextColor = BrickColor.new("Mid gray")
TextLabel508.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel508.TextSize = 28
TextLabel508.TextWrap = true
TextLabel508.TextWrapped = true
Frame509.Name = "OtherTab"
Frame509.Parent = Frame506
Frame509.Position = UDim2.new(0.526000082, 0, 0.711140096, 0)
Frame509.Size = UDim2.new(0, 424, 0, 278)
Frame509.BackgroundColor = BrickColor.new("Really black")
Frame509.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame509.BorderColor = BrickColor.new("Dirt brown")
Frame509.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame509.BorderSizePixel = 2
TextLabel510.Name = "Other"
TextLabel510.Parent = Frame509
TextLabel510.Position = UDim2.new(0.0361394361, 0, -0.0417935476, 0)
TextLabel510.Size = UDim2.new(0, 68, 0, 12)
TextLabel510.Active = true
TextLabel510.BackgroundColor = BrickColor.new("Really black")
TextLabel510.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel510.BorderColor = BrickColor.new("Really black")
TextLabel510.BorderColor3 = Color3.new(0, 0, 0)
TextLabel510.BorderSizePixel = 0
TextLabel510.ZIndex = 2
TextLabel510.Font = Enum.Font.SourceSansBold
TextLabel510.FontSize = Enum.FontSize.Size28
TextLabel510.Text = "Other"
TextLabel510.TextColor = BrickColor.new("Mid gray")
TextLabel510.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel510.TextSize = 28
TextLabel510.TextWrap = true
TextLabel510.TextWrapped = true
Frame511.Name = "TriggerbotTab"
Frame511.Parent = Frame506
Frame511.Position = UDim2.new(0.526000082, 0, 0.169949651, 0)
Frame511.Size = UDim2.new(0, 424, 0, 485)
Frame511.BackgroundColor = BrickColor.new("Really black")
Frame511.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
Frame511.BorderColor = BrickColor.new("Dirt brown")
Frame511.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame511.BorderSizePixel = 2
TextLabel512.Name = "Triggerbot"
TextLabel512.Parent = Frame511
TextLabel512.Position = UDim2.new(0.0361394361, 0, -0.0180409849, 0)
TextLabel512.Size = UDim2.new(0, 114, 0, 10)
TextLabel512.Active = true
TextLabel512.BackgroundColor = BrickColor.new("Really black")
TextLabel512.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
TextLabel512.BorderColor = BrickColor.new("Really black")
TextLabel512.BorderColor3 = Color3.new(0, 0, 0)
TextLabel512.BorderSizePixel = 0
TextLabel512.ZIndex = 2
TextLabel512.Font = Enum.Font.SourceSansBold
TextLabel512.FontSize = Enum.FontSize.Size28
TextLabel512.Text = "Triggerbot"
TextLabel512.TextColor = BrickColor.new("Mid gray")
TextLabel512.TextColor3 = Color3.new(0.827451, 0.827451, 0.827451)
TextLabel512.TextSize = 28
TextLabel512.TextWrap = true
TextLabel512.TextWrapped = true
Frame513.Name = "color bar"
Frame513.Parent = Frame17
Frame513.Position = UDim2.new(0.5, 0, 0.00100000005, 0)
Frame513.Size = UDim2.new(0.904999971, 105, 0, 1)
Frame513.Active = true
Frame513.AnchorPoint = Vector2.new(0.5, 0.5)
Frame513.BackgroundColor = BrickColor.new("Institutional white")
Frame513.BackgroundColor3 = Color3.new(1, 1, 1)
Frame513.BorderColor = BrickColor.new("Institutional white")
Frame513.BorderColor3 = Color3.new(1, 1, 1)
Frame513.ZIndex = 10
LocalScript514.Name = "Color"
LocalScript514.Parent = Frame513
table.insert(cors,sandbox(LocalScript514,function()
local UIGradient = Instance.new("UIGradient")
UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(61, 139, 234)), ColorSequenceKeypoint.new(0.50, Color3.fromRGB(225, 29, 222)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(235, 252, 38))}
UIGradient.Parent = script.Parent
end))
LocalScript515.Name = "FX"
LocalScript515.Parent = Frame17
table.insert(cors,sandbox(LocalScript515,function()
script.Parent.Parent.Parent["gamesense.pub"].Enabled = false
 Aim = script.Parent.Tabs.Aim
 AA = script.Parent.Tabs.AA
 Legit = script.Parent.Tabs.Legit
 Visuals = script.Parent.Tabs.Visual
 Settings = script.Parent.Tabs.Settings
 Skins = script.Parent.Tabs.Skins
 User = script.Parent.Tabs.User

 AimToggled = false
 AAToggled = false
 LegitToggled = false
 VisualToggled = false
 SettingsToggled = false
 SkinsToggled = false
 UserToggled = false


 userInputService = game:GetService("UserInputService")
 TweenService = game:GetService("TweenService")
 ScreenGui = script.Parent
 MainBackground = script.Parent
 tab = script.Parent.Tabs
 decoration = script.Parent["color bar"]
 load = false

script.Parent.Visible = false
script.Parent.Tabs.Visible = false
script.Parent.Tabs.Aim.Visible = false
script.Parent.Tabs.AA.Visible = false
script.Parent.Tabs.Legit.Visible = false
script.Parent.Tabs.Visual.Visible = false
script.Parent.Tabs.Settings.Visible = false
script.Parent.Tabs.Skins.Visible = false
script.Parent.Tabs.User.Visible = false
script.Parent["color bar"].Visible = false
wait(5)
script.Parent.BackgroundTransparency = 1


if load == false then
	load = true
	script.Parent.Parent.Parent["gamesense.pub"].Enabled = true
	local fadeInTween4 = TweenService:Create(MainBackground, TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 0})
	fadeInTween4:Play()
	local fadeInTween5 = TweenService:Create(tab, TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 0})
	fadeInTween5:Play()
	local fadeInTween6 = TweenService:Create(decoration, TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 0})
	fadeInTween6:Play()
	script.Parent.Visible = true
	script.Parent.Tabs.Visible = true
	script.Parent["color bar"].Visible = true
	script.Parent.Tabs.Aim.Visible = true
	script.Parent.Tabs.AA.Visible = true
	script.Parent.Tabs.Legit.Visible = true
	script.Parent.Tabs.Visual.Visible = true
	script.Parent.Tabs.Settings.Visible = true
	script.Parent.Tabs.Skins.Visible = true
	script.Parent.Tabs.User.Visible = true	
end


userInputService.InputBegan:Connect(function(input, gameProcessedEvent)
	if input.UserInputType == Enum.UserInputType.Keyboard then
		
		if input.KeyCode == Enum.KeyCode.Insert and script.Parent.BackgroundTransparency == 0 then
			
			local fadeOutTween1 = TweenService:Create(MainBackground, TweenInfo.new(0.25, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 1})
			fadeOutTween1:Play()
			local fadeOutTween2 = TweenService:Create(tab, TweenInfo.new(0.25, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 1})
			fadeOutTween2:Play()
			local fadeOutTween3 = TweenService:Create(decoration, TweenInfo.new(0.25, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 1})
			fadeOutTween3:Play()
			script.Parent.Tabs.Aim.Visible = false
			script.Parent.Tabs.AA.Visible = false
			script.Parent.Tabs.Legit.Visible = false
			script.Parent.Tabs.Visual.Visible = false
			script.Parent.Tabs.Settings.Visible = false
			script.Parent.Tabs.Skins.Visible = false
			script.Parent.Tabs.User.Visible = false
			script.Parent["color bar"].Visible = false
			wait(0.25)
			script.Parent.Visible = false
			
		else if input.KeyCode == Enum.KeyCode.Insert and script.Parent.BackgroundTransparency == 1 then
				
				local fadeInTween4 = TweenService:Create(MainBackground, TweenInfo.new(0.25, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 0})
				fadeInTween4:Play()
				local fadeInTween5 = TweenService:Create(tab, TweenInfo.new(0.25, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 0})
				fadeInTween5:Play()
				local fadeInTween6 = TweenService:Create(decoration, TweenInfo.new(0.25, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, 0, false, 0), {BackgroundTransparency = 0})
				fadeInTween6:Play()
				wait(0.15)	
				
				script.Parent.Visible = true
				script.Parent.Tabs.Visible = true
				script.Parent["color bar"].Visible = true
				script.Parent.Tabs.Aim.Visible = true
				script.Parent.Tabs.AA.Visible = true
				script.Parent.Tabs.Legit.Visible = true
				script.Parent.Tabs.Visual.Visible = true
				script.Parent.Tabs.Settings.Visible = true
				script.Parent.Tabs.Skins.Visible = true
				script.Parent.Tabs.User.Visible = true
				script.Parent["color bar"].Visible = true
			end
		end
		
	end
end)

while true do
		if Aim.Icon.ImageColor3 == Color3.fromRGB(255, 255, 255) and AimToggled == false then
		
		Aim.Main.Visible = true
		Aim["Side Border"].Visible = false
		Aim.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
		AA["Other border"].Visible = true
		
		AA["Side Border"].Visible = true
		AA.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		AA.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		AA.Main.Visible = false
		
		Legit["Side Border"].Visible = true
		Legit.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Legit.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Legit.Main.Visible = false
		Legit["Other border"].Visible = false
		
		Visuals["Side Border"].Visible = true
		Visuals.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Visuals.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Visuals.Main.Visible = false
		Visuals["Other border"].Visible = false
		
		Settings["Side Border"].Visible = true
		Settings.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Settings.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Settings.Main.Visible = false
		Settings["Other border"].Visible = false
		
		Skins["Side Border"].Visible = true
		Skins.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Skins.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Skins.Main.Visible = false
		Skins["Other border"].Visible = false
		
		User["Side Border"].Visible = true
		User.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		User.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		User.Main.Visible = false
		User["Other border"].Visible = false
		
		AimToggled = true
		AAToggled = false
		LegitToggled = false
		VisualToggled = false
		SettingsToggled = false
		SkinsToggled = false
		UserToggled = false
		
	end
	
	if AA.Icon.ImageColor3 == Color3.fromRGB(255, 255, 255) and AAToggled == false then
		
		AA.Main.Visible = true
		AA["Side Border"].Visible = false
		AA.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
		AA["Other border"].Visible = true
		
		Aim["Side Border"].Visible = true
		Aim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Aim.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Aim.Main.Visible = false
		
		Legit["Side Border"].Visible = true
		Legit.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Legit.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Legit.Main.Visible = false
		Legit["Other border"].Visible = true
		
		Visuals["Side Border"].Visible = true
		Visuals.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Visuals.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Visuals.Main.Visible = false
		Visuals["Other border"].Visible = false
		
		Settings["Side Border"].Visible = true
		Settings.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Settings.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Settings.Main.Visible = false
		Settings["Other border"].Visible = false
		
		Skins["Side Border"].Visible = true
		Skins.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Skins.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Skins.Main.Visible = false
		Skins["Other border"].Visible = false
		
		User["Side Border"].Visible = true
		User.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		User.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		User.Main.Visible = false
		User["Other border"].Visible = false
		
		AimToggled = false
		AAToggled = true
		LegitToggled = false
		VisualToggled = false
		SettingsToggled = false
		SkinsToggled = false
		UserToggled = false
		
	end
	
	if Legit.Icon.ImageColor3 == Color3.fromRGB(255, 255, 255) and LegitToggled == false then
		
		Legit.Main.Visible = true
		Legit["Side Border"].Visible = false
		Legit.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
		Legit["Other border"].Visible = true
		
		Aim["Side Border"].Visible = true
		Aim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Aim.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Aim.Main.Visible = false
		
		AA["Side Border"].Visible = true
		AA.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		AA.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		AA.Main.Visible = false
		AA["Other border"].Visible = false
		
		Visuals["Side Border"].Visible = true
		Visuals.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Visuals.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Visuals.Main.Visible = false
		Visuals["Other border"].Visible = true
		
		Settings["Side Border"].Visible = true
		Settings.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Settings.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Settings.Main.Visible = false
		Settings["Other border"].Visible = false
		
		Skins["Side Border"].Visible = true
		Skins.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Skins.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Skins.Main.Visible = false
		Skins["Other border"].Visible = false
		
		User["Side Border"].Visible = true
		User.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		User.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		User.Main.Visible = false
		User["Other border"].Visible = false
		
		AimToggled = false
		AAToggled = false
		LegitToggled = true
		VisualToggled = false
		SettingsToggled = false
		SkinsToggled = false
		UserToggled = false
		
	end
	
	if Visuals.Icon.ImageColor3 == Color3.fromRGB(255, 255, 255) and VisualToggled == false then
		
		Visuals.Main.Visible = true
		Visuals["Side Border"].Visible = false
		Visuals.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
		Visuals["Other border"].Visible = true
		
		Aim["Side Border"].Visible = true
		Aim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Aim.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Aim.Main.Visible = false
		
		AA["Side Border"].Visible = true
		AA.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		AA.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		AA.Main.Visible = false
		AA["Other border"].Visible = false
		
		Legit["Side Border"].Visible = true
		Legit.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Legit.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Legit.Main.Visible = false
		Legit["Other border"].Visible = false
		
		Settings["Side Border"].Visible = true
		Settings.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Settings.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Settings.Main.Visible = false
		Settings["Other border"].Visible = true
		
		Skins["Side Border"].Visible = true
		Skins.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Skins.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Skins.Main.Visible = false
		Skins["Other border"].Visible = false
		
		User["Side Border"].Visible = true
		User.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		User.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		User.Main.Visible = false
		User["Other border"].Visible = false
		
		AimToggled = false
		AAToggled = false
		LegitToggled = false
		VisualToggled = true
		SettingsToggled = false
		SkinsToggled = false
		UserToggled = false
		
	end
	
	if Settings.Icon.ImageColor3 == Color3.fromRGB(255, 255, 255) and SettingsToggled == false then
		
		Settings.Main.Visible = true
		Settings["Side Border"].Visible = false
		Settings.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
		Settings["Other border"].Visible = true
		
		Aim["Side Border"].Visible = true
		Aim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Aim.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Aim.Main.Visible = false
		
		AA["Side Border"].Visible = true
		AA.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		AA.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		AA.Main.Visible = false
		AA["Other border"].Visible = false
		
		Legit["Side Border"].Visible = true
		Legit.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Legit.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Legit.Main.Visible = false
		Legit["Other border"].Visible = false
		
		Visuals["Side Border"].Visible = true
		Visuals.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Visuals.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Visuals.Main.Visible = false
		Visuals["Other border"].Visible = false
		
		Skins["Side Border"].Visible = true
		Skins.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Skins.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Skins.Main.Visible = false
		Skins["Other border"].Visible = true
		
		User["Side Border"].Visible = true
		User.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		User.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		User.Main.Visible = false
		User["Other border"].Visible = false
		
		AimToggled = false
		AAToggled = false
		LegitToggled = false
		VisualToggled = false
		SettingsToggled = true
		SkinsToggled = false
		UserToggled = false
		
	end
	
	if Skins.Icon.ImageColor3 == Color3.fromRGB(255, 255, 255) and SkinsToggled == false then
		
		Skins.Main.Visible = true
		Skins["Side Border"].Visible = false
		Skins.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
		Skins["Other border"].Visible = true
		
		Aim["Side Border"].Visible = true
		Aim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Aim.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Aim.Main.Visible = false
		
		AA["Side Border"].Visible = true
		AA.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		AA.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		AA.Main.Visible = false
		AA["Other border"].Visible = false
		
		Legit["Side Border"].Visible = true
		Legit.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Legit.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Legit.Main.Visible = false
		Legit["Other border"].Visible = false
		
		Settings["Side Border"].Visible = true
		Settings.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Settings.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Settings.Main.Visible = false
		Settings["Other border"].Visible = false
		
		Visuals["Side Border"].Visible = true
		Visuals.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Visuals.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Visuals.Main.Visible = false
		Visuals["Other border"].Visible = false
		
		User["Side Border"].Visible = true
		User.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		User.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		User.Main.Visible = false
		User["Other border"].Visible = true
		
		AimToggled = false
		AAToggled = false
		LegitToggled = false
		VisualToggled = false
		SettingsToggled = false
		SkinsToggled = true
		UserToggled = false
		
	end
	
	
	if User.Icon.ImageColor3 == Color3.fromRGB(255, 255, 255) and UserToggled == false then
		
		User.Main.Visible = true
		User["Side Border"].Visible = false
		User.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
		User["Other border"].Visible = true
		
		Aim["Side Border"].Visible = true
		Aim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Aim.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Aim.Main.Visible = false
		
		AA["Side Border"].Visible = true
		AA.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		AA.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		AA.Main.Visible = false
		AA["Other border"].Visible = false
		
		Legit["Side Border"].Visible = true
		Legit.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Legit.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Legit.Main.Visible = false
		Legit["Other border"].Visible = false
		
		Settings["Side Border"].Visible = true
		Settings.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Settings.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Settings.Main.Visible = false
		Settings["Other border"].Visible = false
		
		Visuals["Side Border"].Visible = true
		Visuals.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Visuals.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Visuals.Main.Visible = false
		Visuals["Other border"].Visible = false
		
		Skins["Side Border"].Visible = true
		Skins.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		Skins.Icon.ImageColor3 = Color3.fromRGB(143, 143, 143)
		Skins.Main.Visible = false
		Skins["Other border"].Visible = false
		
		AimToggled = false
		AAToggled = false
		LegitToggled = false
		VisualToggled = false
		SettingsToggled = false
		SkinsToggled = false
		UserToggled = true
		
	end
	wait(0.1)
	
end
end))
UIScale516.Parent = Frame17
LocalScript517.Name = "Autoscale"
LocalScript517.Parent = UIScale516
table.insert(cors,sandbox(LocalScript517,function()
-- This script will scale the menu according to the size of the screen
local x = workspace.CurrentCamera.ViewportSize.X
local y = workspace.CurrentCamera.ViewportSize.Y
local Scale = script.Parent


if y == 2560 then
	Scale.Scale = 0.65
end

if y == 1440 then
	Scale.Scale = 0.5
end

if y == 1080 then
	Scale.Scale = 0.5
end

if y == 768 then
	Scale.Scale = 0.35
end

if y == 720 then
	Scale.Scale = 0.35

end
	
if x == 3480 then
	Scale.Scale = 0.65
end
	
if x == 2560 then
	Scale.Scale = 0.5
end
	
if x == 1920 then
	Scale.Scale = 0.5
end
	
if x == 1366 then
	Scale.Scale = 0.35
end
	
if x == 768 then
	Scale.Scale = 0.35
end

end))
LocalScript518.Name = "Draggable menu and move mouse"
LocalScript518.Parent = ScreenGui0
table.insert(cors,sandbox(LocalScript518,function()
frame = script.Parent.Main
frame.Draggable = true
frame.Active = true
frame.Selectable = true


print("[gamesense] injecting...")
wait(5)
print("[gamesense] injected")

local cursor2 = Instance.new("ImageLabel")


cursor2.Name = "cursor"
cursor2.Parent = script.Parent
cursor2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
cursor2.BackgroundTransparency = 1.000
cursor2.Position = UDim2.new(-1, 0, -1, 0)
cursor2.Rotation = 19.000
cursor2.Size = UDim2.new(0, 12, 0, 16)
cursor2.Image = "rbxassetid://5751165696"
cursor2.ScaleType = Enum.ScaleType.Fit
cursor2.ZIndex = 999

 Main = script.Parent.Main
 cursor = script.Parent.cursor


function onKeyPress(inputObject, gameProcessedEvent)
	if inputObject.KeyCode == Enum.KeyCode.Insert then
		
		if Main.Visible == true then
			wait(0.25)
			Main.Visible = false
		else
			Main.Visible = true
		end
	end
end

game:GetService("UserInputService").InputBegan:connect(onKeyPress)

game['Run Service'].Stepped:connect(function()
	
	local mouse = game.Players.LocalPlayer:GetMouse()
	cursor.Position = UDim2.new(0, mouse.X, 0, mouse.Y)
	
	if Main.Visible == true then 
		cursor.Visible = true
	else
		cursor.Visible = false
	end
	
	
	
	
	if Main.Visible == true then
		game:GetService("UserInputService").MouseBehavior = Enum.MouseBehavior.Default
		
	else
		
		game:GetService("UserInputService").MouseBehavior = Enum.MouseBehavior.LockCenter
	end
end)

end))
Frame519.Name = "Watermark"
Frame519.Parent = ScreenGui0
Frame519.Position = UDim2.new(0.860000014, 0, 0.237000003, 0)
Frame519.Visible = false
Frame519.Size = UDim2.new(0, 764, 0, 30)
Frame519.BackgroundColor = BrickColor.new("Really black")
Frame519.BackgroundColor3 = Color3.new(0.0666667, 0.0666667, 0.0666667)
Frame519.BorderColor = BrickColor.new("Dirt brown")
Frame519.BorderColor3 = Color3.new(0.262745, 0.262745, 0.262745)
Frame519.BorderSizePixel = 2
Frame519.SizeConstraint = Enum.SizeConstraint.RelativeXX
Frame519.ZIndex = 999999998
TextLabel520.Name = "Bloxsense"
TextLabel520.Parent = Frame519
TextLabel520.Position = UDim2.new(0.0100001786, 0, 0, 0)
TextLabel520.Size = UDim2.new(0, 467, 0, 30)
TextLabel520.BackgroundColor = BrickColor.new("Institutional white")
TextLabel520.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel520.BackgroundTransparency = 1
TextLabel520.BorderSizePixel = 0
TextLabel520.ZIndex = 999999999
TextLabel520.Font = Enum.Font.SourceSans
TextLabel520.FontSize = Enum.FontSize.Size24
TextLabel520.Text = "Bloxsense             |                |                 |                  |"
TextLabel520.TextColor = BrickColor.new("Institutional white")
TextLabel520.TextColor3 = Color3.new(1, 1, 1)
TextLabel520.TextSize = 23
TextLabel520.TextXAlignment = Enum.TextXAlignment.Left
LocalScript521.Name = "Color"
LocalScript521.Parent = TextLabel520
table.insert(cors,sandbox(LocalScript521,function()
UIGradient = Instance.new("UIGradient")
UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(184, 255, 69)), ColorSequenceKeypoint.new(0.25, Color3.fromRGB(184, 255, 69)), ColorSequenceKeypoint.new(0.26, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Parent = script.Parent
end))
LocalScript522.Name = "Main"
LocalScript522.Parent = Frame519
table.insert(cors,sandbox(LocalScript522,function()
local RunService = game:GetService("RunService")
local fps = 0
local Stats = game:GetService("Stats")
local floor = math.floor
local MEMUsage = script.Parent.MB
local BaseFrame = script.Parent
local TimeTitle = BaseFrame.Time



function updateFPS()
	fps = fps + 1
end

RunService.RenderStepped:connect(updateFPS)
while wait(1) do
	script.Parent.FPS.Text = fps .." FPS"
	fps = 0

	seconds = os.date("*t") ["sec"]
	minutes = os.date("*t") ["min"]
	hours = os.date("*t") ["hour"]

	if tonumber(seconds) <= 9 then
		seconds = "0"..seconds
	end
	if tonumber(minutes) <= 9 then
		minutes = "0"..minutes
	end
	if tonumber(hours) <= 9 then
		hours = "0"..hours
	end

	TimeTitle.Text = hours..":"..minutes..":"..seconds
	MEMUsage.Text = floor(Stats:GetTotalMemoryUsageMb()) .." MB"
end
end))
LocalScript523.Name = "RGB"
LocalScript523.Parent = Frame519
table.insert(cors,sandbox(LocalScript523,function()
t = 5; --how long does it take to go through the rainbow
local B = script.Parent.B
local E = script.Parent.E
local T = script.Parent.T
local A = script.Parent.A
local tick = tick

local fromHSV = Color3.fromHSV
local RunService = game:GetService("RunService")


RunService:BindToRenderStep("Rainbow", 1000, function()
	local hue = tick() % t / t
	local color = fromHSV(hue, 1, 1)
	B.TextColor3 = color
end)
RunService:BindToRenderStep("Rainbow", 1000, function()
	local hue = tick() % t / t
	local color = fromHSV(hue, 1, 1)
	wait(0.3)
	E.TextColor3 = color
end)
RunService:BindToRenderStep("Rainbow", 1000, function()
	local hue = tick() % t / t
	local color = fromHSV(hue, 1, 1)
	wait(0.6)
	T.TextColor3 = color
end)
RunService:BindToRenderStep("Rainbow", 1000, function()
	local hue = tick() % t / t
	local color = fromHSV(hue, 1, 1)
	wait(0.9)
	A.TextColor3 = color
end)

end))
TextLabel524.Name = "B"
TextLabel524.Parent = Frame519
TextLabel524.Position = UDim2.new(0.113607839, 0, 0, 0)
TextLabel524.Size = UDim2.new(0, 19, 0, 30)
TextLabel524.BackgroundColor = BrickColor.new("Really black")
TextLabel524.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel524.BackgroundTransparency = 1
TextLabel524.BorderSizePixel = 0
TextLabel524.ZIndex = 999999999
TextLabel524.Font = Enum.Font.SourceSans
TextLabel524.FontSize = Enum.FontSize.Size28
TextLabel524.Text = "B"
TextLabel524.TextColor = BrickColor.new("Institutional white")
TextLabel524.TextColor3 = Color3.new(1, 1, 1)
TextLabel524.TextSize = 26
TextLabel524.TextWrap = true
TextLabel524.TextWrapped = true
TextLabel525.Name = "E"
TextLabel525.Parent = Frame519
TextLabel525.Position = UDim2.new(0.126848623, 0, 0, 0)
TextLabel525.Size = UDim2.new(0, 19, 0, 30)
TextLabel525.BackgroundColor = BrickColor.new("Really black")
TextLabel525.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel525.BackgroundTransparency = 1
TextLabel525.BorderSizePixel = 0
TextLabel525.ZIndex = 999999999
TextLabel525.Font = Enum.Font.SourceSans
TextLabel525.FontSize = Enum.FontSize.Size28
TextLabel525.Text = "E"
TextLabel525.TextColor = BrickColor.new("Institutional white")
TextLabel525.TextColor3 = Color3.new(1, 1, 1)
TextLabel525.TextSize = 26
TextLabel525.TextWrap = true
TextLabel525.TextWrapped = true
TextLabel526.Name = "T"
TextLabel526.Parent = Frame519
TextLabel526.Position = UDim2.new(0.141726822, 0, 0, 0)
TextLabel526.Size = UDim2.new(0, 19, 0, 30)
TextLabel526.BackgroundColor = BrickColor.new("Really black")
TextLabel526.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel526.BackgroundTransparency = 1
TextLabel526.BorderSizePixel = 0
TextLabel526.ZIndex = 999999999
TextLabel526.Font = Enum.Font.SourceSans
TextLabel526.FontSize = Enum.FontSize.Size28
TextLabel526.Text = "T"
TextLabel526.TextColor = BrickColor.new("Institutional white")
TextLabel526.TextColor3 = Color3.new(1, 1, 1)
TextLabel526.TextSize = 26
TextLabel526.TextWrap = true
TextLabel526.TextWrapped = true
TextLabel527.Name = "A"
TextLabel527.Parent = Frame519
TextLabel527.Position = UDim2.new(0.155866519, 0, 0, 0)
TextLabel527.Size = UDim2.new(0, 19, 0, 30)
TextLabel527.BackgroundColor = BrickColor.new("Really black")
TextLabel527.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel527.BackgroundTransparency = 1
TextLabel527.BorderSizePixel = 0
TextLabel527.ZIndex = 999999999
TextLabel527.Font = Enum.Font.SourceSans
TextLabel527.FontSize = Enum.FontSize.Size28
TextLabel527.Text = "A"
TextLabel527.TextColor = BrickColor.new("Institutional white")
TextLabel527.TextColor3 = Color3.new(1, 1, 1)
TextLabel527.TextSize = 26
TextLabel527.TextWrap = true
TextLabel527.TextWrapped = true
TextLabel528.Name = "FPS"
TextLabel528.Parent = Frame519
TextLabel528.Position = UDim2.new(0.190308899, 0, 0, 0)
TextLabel528.Size = UDim2.new(0, 57, 0, 30)
TextLabel528.BackgroundColor = BrickColor.new("Institutional white")
TextLabel528.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel528.BackgroundTransparency = 1
TextLabel528.BorderSizePixel = 0
TextLabel528.ZIndex = 999999999
TextLabel528.Font = Enum.Font.SourceSans
TextLabel528.FontSize = Enum.FontSize.Size24
TextLabel528.Text = "100 FPS"
TextLabel528.TextColor = BrickColor.new("Institutional white")
TextLabel528.TextColor3 = Color3.new(1, 1, 1)
TextLabel528.TextSize = 23
TextLabel529.Name = "MB"
TextLabel529.Parent = Frame519
TextLabel529.Position = UDim2.new(0.278382301, 0, 0, 0)
TextLabel529.Size = UDim2.new(0, 65, 0, 30)
TextLabel529.BackgroundColor = BrickColor.new("Institutional white")
TextLabel529.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel529.BackgroundTransparency = 1
TextLabel529.BorderSizePixel = 0
TextLabel529.ZIndex = 999999999
TextLabel529.Font = Enum.Font.SourceSans
TextLabel529.FontSize = Enum.FontSize.Size24
TextLabel529.Text = "1000 MB"
TextLabel529.TextColor = BrickColor.new("Institutional white")
TextLabel529.TextColor3 = Color3.new(1, 1, 1)
TextLabel529.TextSize = 23
TextLabel530.Name = "Time"
TextLabel530.Parent = Frame519
TextLabel530.Position = UDim2.new(0.37605229, 0, 0, 0)
TextLabel530.Size = UDim2.new(0, 67, 0, 30)
TextLabel530.BackgroundColor = BrickColor.new("Institutional white")
TextLabel530.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel530.BackgroundTransparency = 1
TextLabel530.BorderSizePixel = 0
TextLabel530.ZIndex = 999999999
TextLabel530.Font = Enum.Font.SourceSans
TextLabel530.FontSize = Enum.FontSize.Size24
TextLabel530.Text = "00:00:00"
TextLabel530.TextColor = BrickColor.new("Institutional white")
TextLabel530.TextColor3 = Color3.new(1, 1, 1)
TextLabel530.TextSize = 23
for i,v in pairs(mas:GetChildren()) do
	v.Parent = game.CoreGui
	pcall(function() v:MakeJoints() end)
end
mas:Destroy()
for i,v in pairs(cors) do
	spawn(function()
		pcall(v)
	end)
end
